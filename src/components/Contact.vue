<!-- Amanda -->

<template>
    <section id="contact" class="contact-area">
        <div>
            <div class="container">
                <div class="contact-row">
                    <div class="justify-content-center">
                        <div class="col-lg-6 col-12">
                            <div class="contact-title">
                                <h2>Let's Talk</h2>
                                <p>Must explain to you how all this mistaken idea of denouncing pleasure born and give you a complete account the system</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="contact-row">
                    <div class="co-lg-10 offset-lg-1  col-12">
                        <div class="contact-row">
                            <div class="col col-lg-6 col-md-12 col-12">
                                <div class="contact-form">
                                    <h2>Get in Touch</h2>
                                    <form class="validation-contact">
                                        <div class="contact-row">
                                            <div class="col col-lg-6 col-12">
                                                <div class="form-field">
                                                    <input type="text" value="" name="name" placeholder="Your Name">
                                                    <div class="errorMessage" style="display: none;">The name field is required.</div>
                                                </div>
                                            </div>
                                            <div class="col col-lg-6 col-12">
                                                <div class="form-field">
                                                    <input type="email" value="" name="email" placeholder="Your Email">
                                                    <div class="errorMessage" style="display: none;">The email field is required.</div>
                                                </div>
                                            </div>
                                            <div class="col col-lg-12 col-12">
                                                <div class="form-field">
                                                    <input type="phone" value="" name="phone" placeholder="Your phone">
                                                    <div class="errorMessage" style="display: none;">The phone field is required.</div>
                                                </div>
                                            </div>
                                            <div class="col col-lg-12 col-12">
                                                <div class="form-field">
                                                    <select type="text" name="subject">
                                                        <option>Choose a Service</option>
                                                        <option>Web Design</option>
                                                        <option>Web Development</option>
                                                        <option>Marketing</option>
                                                    </select>
                                                    <div class="errorMessage" style="display: none;">Please select a subject.</div>
                                                </div>
                                            </div>
                                            <div class="col col-lg-12 col-12">
                                                <div class="form-field">
                                                    <textarea type="text" name="message" placeholder="Message"></textarea>
                                                </div>
                                                <div class="errorMessage" style="display: none;">The message field is required.</div>
                                            </div>
                                        </div>
                                        <div class="submit-area">
                                            <button type="submit" class="theme-btn">Submit Now</button>
                                        </div>
                                    </form>
                                </div>
                            </div>
                            <div class="col col-lg-6 col-md-12 col-12">
                                <div class="contact-info">
                                    <div class="info-item">
                                        <h2>25 North Street,Dubai</h2>
                                        <div class="info-wrap">
                                            <div class="info-icon">
                                                <img class="icon" src="../assets/geo-alt-fill.svg">
                                            </div>
                                            <div class="info-text">
                                                <span>Office Address</span>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="info-item">
                                        <h2>info@elito.com</h2>
                                        <div class="info-wrap">
                                            <div class="info-icon">
                                                <img class="icon" src="../assets/envelope-at.svg">
                                            </div>
                                            <div class="info-text">
                                                <span>Official Mail</span>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="info-item">
                                        <h2>+91 256-987-239</h2>
                                        <div class="info-wrap">
                                            <div class="info-icon">
                                                <img class="icon" src="../assets/telephone-forward.svg">
                                            </div>
                                            <div class="info-text">
                                                <span>Official Phone</span>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>
      
<script>
export default {
    name: 'Contact'
}
document.addEventListener("DOMContentLoaded", function() {
    var form = document.querySelector('.validation-contact');
    
    form.addEventListener('submit', function(event) {
        event.preventDefault(); // Prevent the form from submitting
        
        // Check if all fields are filled
        var isValid = true;
        var errorMessageElements = form.querySelectorAll('.errorMessage');
        
        errorMessageElements.forEach(function(errorMessage) {
            errorMessage.style.display = 'none'; // Hide any previous error messages
        });
        
        var inputs = form.querySelectorAll('input, textarea');
        inputs.forEach(function(input) {
            if (!input.value.trim() && input.type !== 'submit') {
                isValid = false;
                var errorMessage;
                if (input.tagName === 'TEXTAREA') {
                    errorMessage = input.parentElement.nextSibling;
                } else {
                    errorMessage = input.parentElement.querySelector('.errorMessage');
                }
                if(errorMessage) {
                    errorMessage.style.display = 'block';
                }
            }
        });

        
        // If everything is valid, submit the form
        if (isValid) {
            // Here you can submit the form using AJAX or any other method
            // For demonstration purposes, we'll just log a message
            console.log('Form submitted successfully');
            // Clear form fields after submission
            form.reset();
        }
    });
});

</script>

<style scoped>

.errorMessage {
    color: red;
}

.wpo-contact-area {
    background: #131313;
    padding-bottom: 40px !important;
    position: relative;
    overflow: hidden;
    z-index: 1;
}

.offset-lg-1 {
    margin-left: 20%;
    }

.contact-row {
    justify-content: center; /* Centra orizzontalmente il contenuto */
    align-items: center; /* Centra verticalmente il contenuto */
    --bs-gutter-x: 1.5rem;
    --bs-gutter-y: 0;
    display: flex;
    flex-wrap: wrap;
    margin-top: calc(-1 * var(--bs-gutter-y));
    margin-right: calc(-.5 * var(--bs-gutter-x));
    margin-left: calc(-.5 * var(--bs-gutter-x));
}

.justify-content-center {
    display: flex;
    justify-content: center !important;
}

.contact-title, .wpo-section-title-s2 {
    margin-bottom: 60px;
    text-align: center;
}

.contact-title h2 {
    font-size: 48px;
    line-height: 55px;
    font-family: Inter,sans-serif;
    font-weight: 700;
    color: #fff;
    display: inline-block;
    padding-bottom: 20px;
    position: relative;
    margin: 10px 0 0;
}

.contact-title p {
    font-size: 18px;
    color: #d8d8d8;
    margin-bottom: 0;
}

.contact-title {
    margin-bottom: 60px;
    text-align: center;
}

.contact-form-map, .contact-form {
    padding: 60px 65px 30px;
    box-shadow: 0 5px 15px 0 rgba(68,68,68,.1);
    border-radius: 5px;
    background: #222121;
    border: 1px solid #464646;
}

.contact-form-map, .form-field {
    margin-bottom: 21px;
}

.wpo-wpo-contact-form-map, .submit-area {
    width: 100%;
    float: none;
    clear: both;
    text-align: center;
    margin-top: 30px;
}

.contact-form form input, .contact-form form select, .contact-form form textarea {
    background: transparent;
    width: 100%;
    height: 50px;
    border: 0;
    border-bottom-width: 0px;
    border-bottom-style: none;
    border-bottom-color: currentcolor;
    border-bottom: 1px solid #464646;
    border-radius: 0;
    box-shadow: none !important;
    padding-left: 0;
    color: #fff;
}
button, input, optgroup, select, textarea {
    margin: 0;
    font-family: inherit;
    font-size: inherit;
    line-height: inherit;
}

.contact-form form select {
    display: inline-block;
    cursor: pointer;
    opacity: 1;
    margin-left: -5px;
}

select {
    word-wrap: normal;
}
button, select {
    text-transform: none;
}

.contact-form form select option {
    color: #202020;
}


.contact-form .theme-btn, .contact-form .view-cart-btn {
    color: #fff;
    outline: none;
    margin-top: 20px;
    border-radius: 40px;
}
[type="button"]:not(:disabled), [type="reset"]:not(:disabled), [type="submit"]:not(:disabled), button:not(:disabled) {
    cursor: pointer;
}
[type="button"]:not(:disabled), [type="reset"]:not(:disabled), [type="submit"]:not(:disabled), button:not(:disabled) {
    cursor: pointer;
}
.contact-form form button {
    padding-bottom: 16px;
}
.theme-btn, .view-cart-btn {
    background: #59c378;
    color: #fff;
    display: inline-block;
    font-weight: 600;
    padding: 15px 65px 15px 35px;
    padding-bottom: 15px;
    border: 0;
    border-radius: 40px;
    text-transform: capitalize;
    backface-visibility: hidden;
    -webkit-backface-visibility: hidden;
    z-index: 1;
    position: relative;
    font-size: 16px;
    font-size: 1.0666666667rem;
    cursor: pointer;
}

.contact-info {
    max-width: 395px;
    padding-left: 20px;
}
.info-item {
    box-shadow: 0 10px 40px 0 rgba(50,50,50,.1);
    padding: 33px 40px;
    margin-bottom: 30px;
    background: #222121;
    border: 1px solid #464646;
    border-radius: 5px;
}

.info-icon {
    width: 90px;
    height: 90px;
    background: #2e2e2e;
    line-height: 90px;
    border-radius: 50%;
    box-shadow: 0 10px 40px 0 rgba(50,50,50,.1);
    text-align: center;
    margin-right: 20px;
    align-items: center;
}

.icon {
    width: 50%;
}
.info-wrap {
    display: flex;
    align-items: center;
}
.info-item h2 {
    font-size: 24px;
    color: #fff;
    font-weight: 600;
    margin-top: 0;
    margin-bottom: 15px;
}

.contact-form h2 {
    font-size: 30px;
    font-size: 1.875rem;
    font-weight: 600;
    margin: 0 0 1em;
    text-align: center;
    color: #fff;
}

.contact-form form :-moz-placeholder, .contact-form form ::placeholder {
    font-style: 16px;
    font-style: normal;
    color: #fff;
}

.col-lg-12 {
    flex: 0 0 auto;
    width: 100%;
    }

    .contact-form form textarea {
    height: 172px;
}

textarea {
    resize: vertical;
}
</style>