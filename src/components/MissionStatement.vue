<template>
  <div class="mission">
    <br>
    <b-container-fluid>
      <b-row class="text-left" style="margin-left:1rem;">
        <b-col xl="12"><h1>{{msg}}</h1></b-col>
      </b-row>
      <br>
      <b-row class="text-left" style="margin: 0 2rem 0 1rem;">
        <b-col xl="12"><span style="white-space: pre-wrap;">{{body}}</span></b-col>
      </b-row>
    </b-container-fluid>
  </div>
</template>

<script>
export default {
  name: 'mission',
  data () {
    return {
      msg: 'MY MISSION',
      body: "Imagine being one of the individuals that have pushed humanity further in its existence. \n" + "\n" +
              "Imagine building an entity from nothing. Creating an existence that was not there previously. Filling a void that was previously unrealized. As humans we have this responsibility. \n" + "\n" +
              "I don’t say ability because that is innate. We have a responsibility to contribute to our evolution. To find and create, to dream and discover, to encourage and be encouraged. You will live a finite amount of days. You will wake up a finite amount of times. Imagine nearing that day, the final day where you will wake up. The final chance in your life to change humanity. Do you want the pain of knowing that you didn’t put your entire being into that goal? Do you want the pain of knowing that you left things undiscovered? Do you want the pain of having not pushed humanity in the direction that you were capable of pushing it in? I will ensure that on my final day, I am filled with the pride of knowing that I gave all that I am capable of giving."
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
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
