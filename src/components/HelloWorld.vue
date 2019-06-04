<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <div>
      <h1>
        {{smallTitle.title}}
      </h1>
      <p
        onselectstart="return false"
        onmousedown="return false"
      >
        {{smallTitle.message}}
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  data() {
    return {
      msg: "Выделите текст",
      smallTitle: {
        title: "Сегодня погода",
        message:
          "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut eget nulla nibh. Donec at quam enim. Morbi porta elementum mauris, mollis sodales dui consectetur eu. Nam rhoncus ligula sit amet metus mollis, id tempor mauris tristique. Suspendisse ipsum ex, dignissim at consectetur eget, tempus vel urna. Morbi faucibus, dolor ac accumsan volutpat, arcu est egestas erat, eget tempor ex nulla scelerisque libero. Sed vehicula pretium quam at interdum. Aliquam commodo ornare nisi non pretium. Curabitur sagittis nulla nec arcu ultrices faucibus a sagittis sem. Etiam pulvinar sapien non cursus dignissim."
      }
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
