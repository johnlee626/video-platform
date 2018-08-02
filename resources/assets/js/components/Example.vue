<template>
    <div class="container">
        <div class="row">
            <div class="col-md-8 col-md-offset-2">
                <div class="panel panel-default">
                    <div class="panel-heading">Example Component</div>

                    <div class="panel-body">
                        I'm an example component!
                    </div>								
                </div>
				
				<div class="card" style="width: 18rem;">
				  <img class="card-img-top" src="" alt="Card image cap" />
				  <div class="card-body">
					<h5 class="card-title">Card title</h5>
					<p class="card-text">Some text</p>
					<a href="#" class="btn btn-primary">Go somewhere</a>
				  </div>
				</div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>
