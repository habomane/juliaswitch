<script>
    export let href;
</script>

<div>
<a class="btn" href={href}> <slot/> </a>
</div>


<style>
.btn {
    padding: 15px 40px;
    background-color: var(--color-green);
    border: 0px;
    color: #222222;
    font-weight: 600;
    border-radius: 3px;
    text-decoration: none;
}

.btn:hover {
    background-color: var(--color-green-hover);
    color: #000000;
}
</style>