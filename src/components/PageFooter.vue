<!-- PageFooter.vue -->
<template>

    <!-- footer : S -->
    <footer class="footer">
      <div class="inner">
<!--        <img src="../../images/logo2.gif" alt="로고" />-->
        <p class="copy">COPYRIGHTⓒ2021 BY SK HOLDINGS CO., LTD. ALL RIGHTS RESERVED.</p>
        <span class="skcc">SK C&C</span>
      </div>
    </footer>
    <!-- footer : E -->

</template>

<script>
export default {}
</script>

<style scoped>
/* FOOTER */
.footer {
  padding: 0 30px;
  border-top: 1px solid #ddd;
}
.footer .inner {
  display: flex;
  align-items: center;
  height: 50px;
  position: relative;
}
.footer .inner img {
  height: 25px;
}
.footer .inner .copy {
  font-size: 11px;
  color: #aaa;
  margin-top: 15px;
  margin-left: 20px;
}
.footer .inner .skcc {
  position: absolute;
  right: 0;
  font-size: 12px;
  color: #666;
}

</style>