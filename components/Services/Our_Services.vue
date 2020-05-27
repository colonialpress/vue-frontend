<template>
    <div class="ourServicesImage">
        <img src="../../assets/header.jpg">
        <p class="services">
            <strong>Our Services</strong>
        </p>
    </div>
</template>
<style>
    .ourServicesImage img {
        width: 100%;
        height: 25%;
    }
    .ourServicesImage {
        position: relative;
        text-align: center;
        color: white;
    }
    .ourServicesImage .services {
        position: absolute;
        top: 50%;
        left: 20%;
        transform: translate(-50%, -50%);
        font-size: 50px;
        width: 25%;
        text-align: left;
    }
</style>
