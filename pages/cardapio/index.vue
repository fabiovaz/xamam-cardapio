<template>
 <main>
   <embed src="/cardapio_primavera.pdf" />
 </main>
</template>
<script>
export default {
  mounted() {
    // window.location.href='./cardapio_primavera.pdf'
    // var a = document.createElement('A')
    // var filePath = './cardapio_primavera.pdf'
    // a.href = filePath
    // a.download = filePath.substr(filePath.lastIndexOf('/') + 1)
    // document.body.appendChild(a)
    // a.click()
    // document.body.removeChild(a)
  }
}
</script>

<style>
embed {
  width: 100vw;
  height: 100vh;
}
</style>

