
<!--should be inherited from the other layout-->

<div id="posts-container">
    <slot></slot>
</div>

<style>
    #posts-container {
        background-color: #111111;
        box-sizing: border-box;
        padding: 25px 10%;
        /* lo siento for hardcoding */
        min-height: calc(100vh - 64px - 46px - 2em);
    }
</style>
