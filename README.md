# -Vue-JS--challenge-4


List rendering:
-	We create a list/array in js file & display each element from that list using v-for
-	Eg: to display an element detail from an array details: <p v-for=”detail from details”>{{detail}}</p>
-	List rendering in case of multiple objects: : <div v-for=”detail from details” :key=”detail.detailId”></div><p>{{detail.productName}}</p>
-	When using v-for it is recommended to give each rendered element its own unique key.
List rendering: https://codepen.io/aparnasoneja/pen/OJvVzJN
