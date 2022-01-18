<template>
 <main>
  <object data="./cardapio_primavera.pdf" type="application/pdf">
    <iframe src="https://docs.google.com/viewer?url=https://xamam-rc.com.br/cardapio_primavera.pdf&embedded=true"></iframe>
  </object>
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
object {
  width: 100vw;
  height: 100vh;
}
</style>

