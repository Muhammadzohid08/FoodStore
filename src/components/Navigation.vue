<script setup>
import Img from "../../public/logo.webp"
</script>


<template>
    <div class="w-full h-auto flex justify-between items-center bg-[rgb(137,199,74)]">
        <div class="w-[50%] h-full flex justify-start items-center px-16 py-4 text-white">
            <a class="text-[14px] border-r-solid border-r-[2px] border-white pr-3 hover:text-black ease-in-out duration-300" href="#"><i class="fa-solid fa-envelope mr-2"></i>info@example.com</a>
            <a class="ml-3 me-2 text-[14px] hover:text-black ease-in-out duration-300" href="#"><i class="fa-solid fa-phone"></i> 0000 - 123456789</a>
        </div>
        <div class="w-[50%] h-full flex justify-end items-center px-16 py-4 text-white ">
            <a class="text-[14px] pr-3 hover:text-black ease-in-out duration-300" href="#"><i class="fa-brands fa-x-twitter"></i></a>
            <a class="ml-5 me-2 text-[14px] hover:text-black ease-in-out duration-300" href="#"><i class="fa-brands fa-square-facebook"></i></a>
            <a class="ml-5 me-2 text-[14px] hover:text-black ease-in-out duration-300" href="#"><i class="fa-brands fa-pinterest"></i></a>
            <a class="ml-5 me-2 text-[14px] hover:text-black ease-in-out duration-300" href="#"><i class="fa-brands fa-instagram"></i></a>
        </div>
    </div>
    <sticky-head class="w-full h-auto flex justify-center items-center flex-col">
        <header class="w-full h-[97px] flex justify-between items-center px-16">
            <img :src="Img" alt="">
            <div class="w-full flex justify-end items-center">
                <ul class="list-none navigarion-ul flex justify-center items-center gap-5 font-bold ">
                    <a class="hover:text-[#89C74A] ease-in-out duration-300" href="#"><li>Home</li></a>
                    <a class="hover:text-[#89C74A] ease-in-out duration-300" href="#"><li>Shop</li></a>
                    <a class="hover:text-[#89C74A] ease-in-out duration-300" href="#"><li>Best Selers <i class="fa-solid fa-chevron-down"></i></li></a>
                    <a class="hover:text-[#89C74A] ease-in-out duration-300" href="#"><li>Deal of the Day</li></a>
                    <a class="hover:text-[#89C74A] ease-in-out duration-300" href="#"><li>Pages</li></a>
                    <a class="hover:text-[#89C74A] ease-in-out duration-300" href="#"><li>Contact us</li></a>
                </ul>
            </div>
        </header>
    </sticky-head>
</template>