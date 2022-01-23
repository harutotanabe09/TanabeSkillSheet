<template>
  <div class="header">
    <h1 class="main">About Me!!</h1>
    <h2 class="description">Server-side engineer</h2>
    <hr />
    <h3>
      <span class="label">Name:</span>
      <span class="value">Haruto Tanabe</span>
    </h3>
    <h3>
      <span class="label">Birth:</span>
      <span class="value">1989/1/11</span>
    </h3>
    <h3>
      <span class="label">Address:</span>
      <span class="value">Tokyo</span>
    </h3>
    <h3>
      <span class="label">Email:</span>
      <span class="value">tana167@yahoo.co.jp</span>
    </h3>
    <h3>
      <span class="label">Qiita:</span>
      <span class="value">
        <a href="https://qiita.com/haruto167">https://qiita.com/haruto167</a>
      </span>
    </h3>
    <h3>
      <span class="label">Github:</span>
      <span class="value">
        <a href="https://github.com/harutotanabe09"
          >https://github.com/harutotanabe09</a
        >
      </span>
    </h3>
    <hr />
  </div>
</template>

<script>
export default {
  name: 'AppHeader',
}
</script>

<style lang="scss" scoped>
.header {
  color: rgb(122, 81, 81);
  .main {
    color: chocolate;
  }
  .label {
    color: gray;
  }
}
</style>
