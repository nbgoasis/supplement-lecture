<template>
  <div id="app">
    <nav>
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/test">Test</router-link> |
      <router-link to="/axiosDataSend2Spring">Vue에서 Spring으로 데이터 전송</router-link> |
      <router-link to="/simple-board-game">보드 게임</router-link> |
      <router-link to="/exercise1">연습 문제 1</router-link> |
      <router-link to="/file-upload-test">파일 업로드 테스트</router-link><br/>
      <router-link to="/board-list">Vue 게시판</router-link> |
      <router-link to="/product-list">상품 게시판</router-link> |
    </nav>
    <router-view/>
  </div>
</template>

<style scoped>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
