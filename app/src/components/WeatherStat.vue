<template>
  <div class="container">
    <i>
      <slot name="icon"></slot>
    </i>
    <div class="content">
      <p>
        <slot name="type"></slot>
      </p>
      <h3>
        <slot name="value"></slot>
      </h3>
    </div>
  </div>
</template>
<style scoped>
.container {
    display: flex;
    background-color: white;
}
.content {
    display: flex;
}
.content p, .content h3 {
    color: black;
}
</style>
