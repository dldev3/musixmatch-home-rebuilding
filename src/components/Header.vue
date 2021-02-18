<template>
    <div class="flex justify-between">
        <div class="flex justify-end p-1">
            <img class="h-5 w-5 mr-2" src="../assets/images/logo.svg" alt="">
            <div class="search-color">
                <p class="text-xs flex items-center">
                    <span class="header-text ml-1 material-icons text-sm">search</span>
                    <span><input class="ml-1 mb-1 w-60 text-xs border-none outline-none search-color text-gray-700" type="text" placeholder="Type song title, artist or lyrics">
                    </span>
                </p>
                
            </div>
        </div>
        <div class="flex justify-start header-font font-bold header-text">
            <p class="p-2 header-text">Top lyrics</p>
            <p class="p-2 header-text">Community</p>
            <p class="p-2 header-text">Contribute</p>
            <p class="p-2 header-text" >Business</p>
            <p class="p-2 font-light" >|</p>
            <p class="p-2 header-text">Sign In</p>
            <p class="p-2 header-text">Sign Up</p>
        </div>
    </div>
</template>

<script>
export default {
    name: "Header"
}
</script>