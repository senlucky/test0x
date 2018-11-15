<template>
  <div id="test">
    <div>
      <script>alert(0)</script>
      <img onerror="alert(1)" src="http://foo.bar/biz" />
      <h2 onmouseover="alert(2)">Test</h2>
    </div>
  </div>


</template>

<script>
</script>

<style>
</style>
