<script lang="ts">
  export let src: string;
  export let alt: string;
  export let className: string = "";
</script>

<img {src} {alt} class="w-full h-full object-cover {className}" />
