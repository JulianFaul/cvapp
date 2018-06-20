<template>
    <f7-page class="homepage" style="background:fff;">
        <f7-navbar>
            <f7-nav-left>
                <f7-link class="panel-open" open-panel="left" icon="fa fa-bars"></f7-link>
            </f7-nav-left>
            <div class="title">Julian Faul</div>
            <f7-nav-right>
                <f7-link class="searchbar-enable" data-searchbar=".searchbar-components" icon="fa fa-search"></f7-link>
            </f7-nav-right>
            <f7-searchbar class="searchbar-components" search-container=".components-list" search-in="a" expandable></f7-searchbar>
        </f7-navbar>
        <div style="position:relative;">
            <div style="width: 100%;background-image: url(http://www.sitea.se/wp-content/uploads/2017/04/slider-main-bg.jpg);height: 130px;background-size: cover;background-repeat: no-repeat;"></div>
            <div style="height: 80px;width: 80px;border-radius: 100%;background-color: rgb(255, 255, 255,0.5);position: absolute;top: 8%;left: 0; margin: 0 auto;right: 0;"></div>
            <div style="position: absolute;top: 75%;left: 0; margin: 0 auto;right: 0; text-align:center; color:#fff;">
                <!-- <p style="padding:0px 0px; margin:0px 0px;">Julian Faul</p> -->
                <small>Front End Web Developer</small>
            </div>
        </div>

        <f7-list class="mainpage-list-items">
            <f7-list-item link="/color-themes/" style="background-image:url(https://www.clearspringacupuncture.co.uk/wp-content/uploads/2013/01/open_book_green_background_1157228291.jpg);background-size: 100%;background-position: 0px -114px;background-repeat: no-repeat;">
           <span style="text-align:center; width:100%;">Bio</span> 
            </f7-list-item>
            <f7-list-item link="/color-themes/" style="background-image:url(https://www.clearspringacupuncture.co.uk/wp-content/uploads/2013/01/open_book_green_background_1157228291.jpg);background-size: 100%;background-position: 0px -114px;background-repeat: no-repeat;">
           <span style="text-align:center; width:100%;">Work Experience</span> 
            </f7-list-item>
            <f7-list-item link="/color-themes/" style="background-image:url(https://www.clearspringacupuncture.co.uk/wp-content/uploads/2013/01/open_book_green_background_1157228291.jpg);background-size: 100%;background-position: 0px -114px;background-repeat: no-repeat;">
           <span style="text-align:center; width:100%;">Education</span> 
            </f7-list-item>
            <f7-list-item link="/color-themes/" style="background-image:url(https://www.clearspringacupuncture.co.uk/wp-content/uploads/2013/01/open_book_green_background_1157228291.jpg);background-size: 100%;background-position: 0px -114px;background-repeat: no-repeat;">
           <span style="text-align:center; width:100%;">Projects</span> 
            </f7-list-item>
        </f7-list>
    </f7-page>
</template>
<script>
export default {};

</script>
