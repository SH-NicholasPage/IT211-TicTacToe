<template>
  <table>
    <tr>
      <td></td>
      <td class="vert"></td>
      <td></td>
    </tr>
    <tr>
      <td class="hori"></td>
      <td class="vert hori"></td>
      <td class="hori"></td>
    </tr>
    <tr>
      <td></td>
      <td class="vert"></td>
      <td></td>
    </tr>
  </table>
</template>

<script>
export default {
  name: 'TicTacToe'
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
td
{
  width: 100px;
  height: 100px;
}

table
{
  margin: 5px auto;
}

.vert
{
  border-left: 2px solid black;
  border-right: 2px solid black;
}

.hori
{
  border-top: 2px solid black;
  border-bottom: 2px solid black;
}
</style>
