vue.
<template>
  <div id="header">
    <h2>헤더</h2>
    <div id="header-logo">
    </div>
    <div id="header-search">
    </div>
    <div id="header-mypage">
      <ul id="header-mypage-ul">
        <li id="header-mypage-li"></li>
        <li id="header-mypage-li"></li>
        <li id="header-mypage-li"></li>
        <li id="header-mypage-li"></li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
#header {
  display: flex;
  justify-content: center;
  align-items: center;
  top: 0;
  width: 100%;
  height: 10vh;
  padding: 0px 30px;
  border: 1px solid #dedede;
}

#header-logo {
}

#logo-img {
}

#header-search{
  display: flex;
  justify-content: center;
}

#header-search-button{
  width: 30px;
  height: 30px;
  margin: 0px 5px;
}

#header-mypage {
}

#header-mypage-ul {
  display: flex;
}

#header-mypage-li {
  list-style: none;
}


</style>
