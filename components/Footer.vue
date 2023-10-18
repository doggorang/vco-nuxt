<template>
    <footer class="section-relative section-top-66 section-bottom-34 page-footer bg-gray-base context-dark">
        <div class="container">
        <div class="row justify-content-md-center text-xl-left">
            <div class="col-md-12">
            <div class="row justify-content-sm-center">
                <div class="col-sm-10 col-md-6 text-sm-left col-lg-6 col-xl-4 order-xl-3 order-lg-2 offset-xxl-1">
                <h6 class="text-uppercase text-spacing-60 text-center text-lg-left">Contact us</h6>
                        <!-- RD Mailform -->
                        <form class="offset-top-34 offset-lg-top-0 text-left" data-form-output="form-output-global" data-form-type="contact" method="post" action="">
                        <div class="form-group">
                            <label class="form-label form-label-sm" for="footer-v2-name">Name:</label>
                            <input class="form-control input-sm form-control-impressed" id="footer-v2-name" type="text" name="name" data-constraints="@Required">
                        </div>
                        <div class="form-group offset-top-20">
                            <label class="form-label form-label-sm" for="footer-v2-email">Your Email*:</label>
                            <input class="form-control input-sm form-control-impressed" id="footer-v2-email" type="text" name="email" data-constraints="@Email @Required">
                        </div>
                        <div class="form-group offset-top-20">
                            <label class="form-label form-label-sm" for="footer-v2-message">Message*:</label>
                            <textarea class="form-control input-sm form-control-impressed" id="footer-v2-message" name="message" data-constraints="@Required" style="height: 80px"></textarea>
                        </div>
                        <div class="group offset-top-20">
                            <button class="btn btn-sm btn-primary" type="submit" style="padding-left: 30px; padding-right: 30px;">submit</button>
                        </div>
                        </form>
                </div>
                <div class="col-sm-12 offset-top-66 col-xl-3 order-xl-1 offset-xl-top-0 order-lg-3">
                <!-- Footer brand-->
                <div class="footer-brand"><a href="/"><img style='margin-top: -5px;margin-left: -15px;' width='218' height='68' src='@/assets/images/logo/logo-footer.png' alt=''/></a></div>
                <p class="text-darker offset-top-4">Get the best dining experience</p>
                <address class="contact-info offset-top-30 p">
                    <div>
                    <dl>
                        <dt class="text-white">Address:</dt>
                        <dd class="text-dark d-xl-block">Tropodo<span class="d-xl-block">60236 Surabaya</span> <span class="d-xl-block">IL 60604-2340.</span></dd>
                    </dl>
                    </div>
                    <div>
                    <dl class="offset-top-0">
                        <dt class="text-white">Telephone:</dt>
                        <dd class="text-dark"><a href="tel:#">+62 800 559 6580</a></dd>
                    </dl>
                    </div>
                    <div>
                    <dl class="offset-top-0">
                        <dt class="text-white">E-mail:</dt>
                        <dd class="text-dark"><a href="mailto:#">veggiesNco@gmail.com</a></dd>
                    </dl>
                    </div>
                </address>
                </div>
                <div class="col-sm-10 col-md-6 offset-top-66 offset-lg-top-0 text-sm-left col-lg-6 col-xl-4 order-xl-2 order-lg-1">
                <h6 class="text-uppercase text-spacing-60 text-center text-lg-left">What people say</h6>
                        <!-- Simple quote Slider-->
                        <div class="owl-carousel owl-carousel-classic owl-carousel-class-light owl-carousel-simple-quote veil-owl-nav" data-items="1" data-nav="false" data-dots="true">
                        <div>
                            <blockquote class="quote quote-simple-2 text-left">
                            <p class="quote-body offset-bottom-0">
                                <q>This is one of the best restaurants I have visited. Everything was excellent. The food was served in a  very creative way. Would recommend to all.</q>
                            </p>
                            <h6 class="quote-author text-uppercase text-white">
                                <cite class="text-normal">- Alex Murphy</cite>
                            </h6>
                            </blockquote>
                        </div>
                        <div>
                            <blockquote class="quote quote-simple-2 text-left">
                            <p class="quote-body offset-bottom-0">
                                <q>Your Restaurant is the best family place for me. It is already a tradition for us to visit this place every Friday evening. I really enjoy everything.</q>
                            </p>
                            <h6 class="quote-author text-uppercase text-white">
                                <cite class="text-normal">- Julia Smith</cite>
                            </h6>
                            </blockquote>
                        </div>
                        <div>
                            <blockquote class="quote quote-simple-2 text-left">
                            <p class="quote-body offset-bottom-0">
                                <q>This is where I go every time I feel overwhelmed with nostalgia or just want to taste the real pasta one more time. Highly recommend.</q>
                            </p>
                            <h6 class="quote-author text-uppercase text-white">
                                <cite class="text-normal">- John Doe</cite>
                            </h6>
                            </blockquote>
                        </div>
                        </div>
                <div class="offset-top-34 text-sm-center text-lg-left">
                        <ul class="list-inline">
                            <li class="list-inline-item"><a class="icon fa fa-facebook icon-xxs icon-circle icon-darkest-filled" href="#"></a></li>
                            <li class="list-inline-item"><a class="icon fa fa-twitter icon-xxs icon-circle icon-darkest-filled" href="#"></a></li>
                            <li class="list-inline-item"><a class="icon fa fa-google-plus icon-xxs icon-circle icon-darkest-filled" href="#"></a></li>
                            <li class="list-inline-item"><a class="icon fa fa-linkedin icon-xxs icon-circle icon-darkest-filled" href="#"></a></li>
                        </ul>
                </div>
                </div>
            </div>
            </div>
        </div>
        </div>
        <div class="container offset-top-50">
        <p class="small text-darker"><span>&copy;&nbsp;</span><span>{{ new Date().getFullYear() }}</span><span>&nbsp;</span><span>Veggies&Co</span>. All Rights Reserved.</p>
        </div>
    </footer>
</template>