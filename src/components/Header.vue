<template>
    <header id="m-hd" class="m-hd">
        <div class="flex-row">
            <a href="http://www.imys.net" target="_blank" class="m-hd-icon" v-waves>
                <i class="icon icon-music icon-lg"></i>
            </a>
            <div class="flex-col ellipsis">Just Music</div>
            <a href="javascript:;" class="m-hd-icon" v-link="{ path: '/search' }" v-waves.circle>
                <i class="icon icon-search icon-lg"></i>
            </a>
            <a href="javascript:;" class="m-hd-icon" v-waves.circle>
                <i class="icon icon-more icon-lg"></i>
            </a>
        </div>
    </header>
</template>

<script>
module.exports = {

};
</script>
