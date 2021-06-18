<template>
  <div id="root">
    <el-header>
      <el-breadcrumb separator="/">
        <el-breadcrumb-item :to="{ path: '/' }"></el-breadcrumb-item>
        <!-- <el-breadcrumb-item :to="{ path: '/about' }">About</el-breadcrumb-item>
        <el-breadcrumb-item :to="{ path: '/profile' }"
          >Profile</el-breadcrumb-item -->
      </el-breadcrumb>
    </el-header>
    <el-main>
      <h1>home</h1>
    </el-main>
  </div>
</template>

<script>
export default {}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
