<template>
    <el-row>
        <el-col :md="18">
            <page-main class="main">
                <iframe src="//player.bilibili.com/player.html?aid=627523969&bvid=BV1Vt4y1i7Sh&cid=249474659&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true" />
            </page-main>
        </el-col>
    </el-row>
</template>

<style lang="scss" scoped>
.main {
    height: 0;
    padding-bottom: 60% !important;
}
iframe {
    border: 1px solid #ccc;
    position: absolute;
    width: calc(100% - 40px);
    height: calc(100% - 40px);
}
</style>
