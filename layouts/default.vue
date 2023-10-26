<template>
    <div>

        <link rel="stylesheet" href="https://pro.fontawesome.com/releases/v5.10.0/css/all.css">
        <link rel="stylesheet" href="style.css">
        <section id="header">
            <div class="icon">
                <a href=""><img src="img/logoIcon.jpg" alt=""></a>
            </div>


            <div>
                <ul id="navbar">
                    <li>
                        <NuxtLink to="/">TRANG CHỦ</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="/shop">SẢN PHẨM</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="/blog">XU HƯỚNG</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="/about">VỀ CHÚNG TÔI</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="/contact">LIÊN HỆ</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="/cart"><i class="fal fa-shopping-bag"></i></NuxtLink>
                    </li>
                    <NuxtLink to="#" id="close"><i class="far fa-times"></i></NuxtLink>
                </ul>
            </div>
            <div id="mobile">
                <li><a href="cart.html"><i class="fal fa-shopping-bag"></i></a></li>
                <i id="bar" class="fas fa-outdent"></i>
            </div>

        </section>
        <div class="container mx-auto p-4">
            <slot />
        </div>
        <footer class="section-p1">
            <div class="col">
                <img class="logo" src="img/logo.png" alt="">
                <h4>Contact</h4>
                <p><strong>Address:</strong> 288 Nguyễn Văn Linh, Phường An Khánh, Quận Ninh Kiều, TP Cần Thơ</p>
                <p><strong>Phone:</strong> +84 897.138.472 / +84 983.194.478</p>
                <p><strong>Hours:</strong> 10:00 - 18:00, Mon - Sat</p>
                <div class="Follow">
                    <h4>Follow us</h4>
                    <div class="icon">
                        <i class="fab fa-facebook-f"></i>
                        <i class="fab fa-twitter"></i>
                        <i class="fab fa-instagram"></i>
                        <i class="fab fa-pinterest-p"></i>
                        <i class="fab fa-youtube"></i>
                    </div>
                </div>
            </div>

            <div class="col">
                <h4>About</h4>
                <a href="#">About us</a>
                <a href="#">Delivery Information</a>
                <a href="#">Privacy Policy</a>
                <a href="#">Terms & Conditions</a>
                <a href="#">Contact Us</a>
            </div>

            <div class="col">
                <h4>My Account</h4>
                <a href="#">Sign In</a>
                <a href="#">View Cart</a>
                <a href="#">My Wishlist</a>
                <a href="#">Track My Order</a>
                <a href="#">Help</a>
            </div>

            <div class="col install">
                <h4>Install App</h4>
                <p>From App Store or Google Play</p>
                <div class="row">
                    <img src="img/pay/app.jpg" alt="">
                    <img src="img/pay/play.jpg" alt="">
                </div>
                <p>Secured Payment Gateways</p>
                <img src="img/pay/pay.png" alt="">
            </div>

            <div class="copyright">
                <p>&copy; 2023 by Doan Van Duy Ecommerce website fashion</p>
            </div>
        </footer>
    </div>
</template>

<script>

</script>

<style scoped>
.router-link-exact-active {
    color: #12b488;
}
</style>