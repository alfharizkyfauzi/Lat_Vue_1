<template>
  <div class="profile">
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-lg-6">
                <div class="media text-left">
                    <img src="../assets/alfhaphoto.jpg" class="user-pic mr-3" >
                    <div class="media-body">
                        <h5 class="mt-0">{{ firstName }} {{lastName}}</h5>
                        <p>{{bio}}</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import 'bootstrap/dist/css/bootstrap.css'

export default {
  name: "Profile",
  data: function(){
    return {
          firstName: 'Alfharizky',
          lastName: 'Fauzi',
          bio: 'Will you do the same for me? Its time to face the music Im no longer your muse.'
    }
  },
  components: {
    // HelloWorld
  },
};
</script>

<style scoped>
.user-pic{
    border-radius: 200%;
    height: 80px;
    width: 80px;
}
</style>