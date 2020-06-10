<template>
    <div>
        <v-container class="yellow darken-1" fluid style="padding:0">
            <v-row class="section" align="center">
                <v-col class="mb-4 textbox" data-aos="slide-left">
                    <h1 class="display-4 font-weight-bold mb-3">
                        yummo <br /><small> online ordering</small>
                    </h1>
                    <h2>
                        The website builder for restaurants, with built in
                        online ordering.
                    </h2>
                </v-col>
            </v-row>
            <v-row
                class="section payment-background"
                data-aos="fade"
                align="center"
            >
                <v-col class="mb-4 white--text textbox">
                    <h1 class="display-4 font-weight-bold mb-3">
                        The future is commission free
                    </h1>
                    <h2>
                        Pay a monthly fee for us to host & manage your website,
                        we charge no commission on orders.
                    </h2>
                </v-col>
            </v-row>
            <v-row class="section " align="center">
                <v-col class="mb-4 black--text textbox">
                    <h1 class="display-4 font-weight-bold mb-3">
                        Why go with yummo?
                    </h1>
                    <ul
                        style="margin-top:50px;max-width:1000px;list-style: none"
                    >
                        <li data-aos="fade-down" class="my-5">
                            <h2>
                                A white label website with online ordering (no commission on orders).
                            </h2>
                        </li>
                        <li data-aos="fade-down" class="my-5">
                            <h2>
                                Focus on the customer experience. A website that
                                looks good! and makes ordering as seamless as
                                possible for users.
                            </h2>
                        </li>
                        <li data-aos="fade-down" class="my-5">
                            <h2>
                                No app to download. Websites built with the
                                latest technology - Progressive Web Apps. Our
                                websites have the features of native mobile
                                applications but don't require the customer to
                                download an app (a customer pain point).
                            </h2>
                        </li>
                    </ul>
                </v-col>
            </v-row>
            <v-row
                class="section taco-background"
                data-aos="fade"
                align="center"
            >
                <v-col class="mb-4 white--text textbox">
                    <h1 class="display-4 font-weight-bold mb-3">
                        How yummo works
                    </h1>
                </v-col>
            </v-row>
            <v-row
                data-aos="fade-down"
                class="black"
                style="padding:0"
                no-gutters
            >
                <h1 class="headline font-weight-bold  black white--text pa-4">
                    1. Sign up. Add menu, opening hours, payment details,
                    delivery fees and areas.
                </h1>
            </v-row>
            <v-row class="section yummo-background">
                <v-col class=" white--text"> </v-col>
            </v-row>
            <v-row
                data-aos="fade-down"
                class="black"
                style="padding:0"
                no-gutters
            >
                <h1 class="headline font-weight-bold  white--text pa-4">
                    2. Customers visit your website and order online
                </h1>
            </v-row>
            <v-row
                class="section text-center"
                align="top"
                style="background:#121212;"
                no-gutters
            >
                <v-col cols="12" md="8" class="text-center mt-4"
                    ><v-img
                        src="@/assets/croppedmenu.png"
                        style="max-width:1000px;margin:0 auto;border-radius:10px;"
                    ></v-img
                ></v-col>
                <v-col cols="12" md="4" class="mt-4">
                    <v-carousel
                        height="700"
                        cycle
                        show-arrows-on-hover
                        style="border-radius:10px;max-width:300px;margin:0 auto"
                    >
                        <v-carousel-item
                            src="@/assets/shopping-cart.png"
                        ></v-carousel-item>
                        <v-carousel-item
                            src="@/assets/user-details.png"
                        ></v-carousel-item>
                        <v-carousel-item
                            src="@/assets/paypal.png"
                        ></v-carousel-item>
                        <v-carousel-item
                            src="@/assets/order-status.png"
                        ></v-carousel-item>
                    </v-carousel>
                </v-col>
            </v-row>
            <v-row
                data-aos="fade-down"
                no-gutters
                style="padding:0"
                class="black"
            >
                <h1 class="headline font-weight-bold   white--text pa-4">
                    3. Manage incoming orders
                </h1></v-row
            >
            <v-row class="section " no-gutters style="padding:0">
                <v-col class=" white--text">
                    <v-img
                        src="@/assets/manage-orders.png"
                        v-if="$vuetify.breakpoint.smAndUp"
                    ></v-img>
                    <v-img src="@/assets/order-mobile.png" v-else></v-img>
                </v-col>
            </v-row>
            <v-row class="section" align="center">
                <v-col class="mb-4 black--text textbox">
                    <h1 class="display-4 font-weight-bold mb-3">
                        Where we're at
                    </h1>
                    <ul style="margin-top:50px;list-style: none">
                        <li data-aos="fade-down" class="my-5">
                            <h2>
                                Yummo is currently in the prototype stage, and
                                about to start a 2 month trial with restaurants
                                from July - September.
                            </h2>
                        </li>
                        <li data-aos="fade-down" class="my-5">
                            <h2>
                                If you would like to take part in our trial or
                                express interest in using Yummo please email
                                kim@bedson.xyz
                            </h2>
                        </li>
                    </ul>
                </v-col>
            </v-row>
            <v-divider></v-divider>
            <v-row class="section " align="center">
                <v-col class="mb-4 black--text textbox">
                    <h1 class="display-4 font-weight-bold mb-3">
                        Team
                    </h1>
                    <v-row style="margin-top:100px" class="text-center">
                        <v-col data-aos="fade-down">
                            <v-img
                                src="@/assets/kim.jpg"
                                style="border-radius:50%;height:250px;width:250px;margin:0 auto"
                            ></v-img>
                            <div class="headline my-5 font-weight-bold">
                                Kim Bedson
                            </div>
                            <div class="title">
                                Founder & Full Stack Developer
                            </div>
                        </v-col>
                        <v-col data-aos="fade-down">
                            <v-img
                                src="@/assets/alex.jpg"
                                style="border-radius:50%;height:250px;width:250px;margin:0 auto"
                            ></v-img>

                            <div class="headline my-5 font-weight-bold">
                                Alex Kuttner
                            </div>
                            <div class="title">Full Stack Developer</div>
                        </v-col>
                        <v-col data-aos="fade-down">
                            <v-img
                                src="@/assets/mariana.jpg"
                                style="border-radius:50%;height:250px;width:250px;margin:0 auto"
                            ></v-img>
                            <div class="headline my-5 font-weight-bold">
                                Mariana Farias
                            </div>
                            <div class="title">UX & Marketing Strategy</div>
                        </v-col>
                    </v-row>
                </v-col>
            </v-row>
        </v-container>
    </div>
</template>

<script>
export default {
    name: 'HelloWorld',

    data: () => ({})
}
</script>
<style>
.textbox {
    max-width: 1000px;
    margin: 0 auto;
    padding: 20px;
}
.section {
    min-height: 100vh;
    max-width: 100vw;
    padding: 20px;
}

.payment-background {
    background-image: url(~@/assets/payment.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    margin-left: 0;
    margin-right: 0;
}



.taco-background {
    background-image: url(~@/assets/taco.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    margin-left: 0;
    margin-right: 0;
}

.yummo-background {
    background-image: url(~@/assets/yummologin.png);
    background-repeat: no-repeat;
    background-size: cover;
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    margin-left: 0;
    margin-right: 0;
}

.manage-orders-background {
    background-image: url(~@/assets/manage-orders.png);
    background-repeat: no-repeat;
    background-size: cover;
    background-position: top center;
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    margin-left: 0;
    margin-right: 0;
}

@media only screen and (max-width: 600px) {
    .section {
        min-height: 70vh;
    }

    .v-application .textbox h1 {
        font-size: 50px !important;
        line-height: 50px;
    }

    .textbox h2 {
        font-size: 24px;
        line-height: 28px;
    }
}
</style>
