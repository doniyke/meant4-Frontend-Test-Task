<template>
    <div class="container-fluid">
      	<div class="rounded shadow p-md-5 p-3 my-3 m-md-5">
          	<div class="row">
				<div class="col-md-6">
					<div>
						<img src="@/assets/contact.svg" alt="" class="img-fluid">
					</div>
				</div>
				<div class="col-md-6">
					<div class="rounded shadow bg-light p-md-5 p-3 form-holder">
						<h3>Reach Out To Us</h3>
						<p>We can't wait to hear form you</p>
						<Form />
					</div>
				</div>
			</div>
      	</div>
    </div>
</template>

<script>
// @ is an alias to /src

import Form from '@/components/Form';
export default {
  name: 'Home',
  components: {
    Form
  }
}
</script>
<style scoped>
	.form-holder{
		color: #999;
	}
	.form-holder h3{
		color: #000;
		font-weight: 900;
	}
</style>
