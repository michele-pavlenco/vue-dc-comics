<template>
    <footer>
        <div class="footer-container">
        <div class="footer-first debug">
a
        </div>
        <div class="footer-second debug">
b
        </div>
        <div class="footer-third debug">
c
        </div>
        </div>
    </footer>
</template>
<script>
export default {
  name: "FooterContent",
};
</script>

<style scoped>
footer{
    width: 100%;
    
}
.footer-container{
    width: 80%;
}
.debug {
  border: 1px solid black;
}
</style>
