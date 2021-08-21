<template>
  <div class="login">
    <div id="di">
      <div class="container">
        <div class="row">
          <div class="col-md-12">
            <form action="" class="form-control">
              <input class="form-control" type="text" v-model="inp" placeholder="msg"/>
              <input class="form-control mt-1" type="password" v-model="inp" placeholder="msg"/>
              <button class="mt-1 btn btn-primary" type="submit">GO</button>
            </form>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
export default {
  name: "login",
  data() {
    return {
      msg: "heo heo",
      palagrape: "adsfasdfasdfasdfasdfasdf",
      inp: "",
    };
  },
};
// export default class HelloWorld extends Vue {
//   @Prop() private msg!: string;
// }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
