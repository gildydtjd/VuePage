vue.<template>
  <div id="main">
    <div>
        <div><h2>router url 통신 : {{ $route.params.name }}</h2></div>
        <div><h2>{{ title }}</h2></div>
    </div>
  </div>
</template>


<script>
import axios from 'axios';

export default {
    data() {
        return {
            title : ''
        }
    },
    created() {
        axios.get("https://jsonplaceholder.typicode.com/todos/1").then(res => {
                this.title = "axios data 통신 : "+ res.data.title;
            }
        )
    }
}
</script>

<style>
#main {
    width: 100%;
    height: 80vh;
    display: flex;
    justify-content: center;
    align-items: center;
}

button{
    width: 30px;
    height: 30px;
}
</style>