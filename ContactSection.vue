<template>
	<section id="contact-section" class="px-12 lg:px-32 py-16 relative">
		<h1 class="uppercase text-5xl mb-4 font-semibold ">
			Sign up
		</h1>
        <div class="grid grid-cols-1 md:grid-cols-2 w-full">

            <div class="flex flex-col w-full items-center">
                <label for="user_studentNumber" class="text-stone-500 text-left">Student Number</label>
                <input type="studentNumber" name="user_studentNumber" id="user_studentNumber" class="bg-stone-200 py-2 px-4 w-full mb-6 xl:w-1/2">

                <label for="user_email" class="text-stone-500 text-left">E-mail address</label>
                <input type="email" name="user_email" id="user_email" class="bg-stone-200 py-2 px-4 w-full mb-6 xl:w-1/2">

                <label for="user_password" class="text-stone-500 text-left">Password</label>
                <input name="user_password" id="user_password" class="bg-stone-200 py-2 px-4 w-full mb-6 xl:w-1/2">

                <button class="btn w-full md:w-1/2">Sign up</button>
            </div>
        </div>
	</section>
</template>

<script>
export default {

}
</script>

<style>
label {
    color: #aaa;
    display: inline-block;
    margin: 25px 0 15px;
    font-size: 0.6em;
    text-transform: uppercase;
    letter-spacing: 1px;
    font-weight: bold;
}
input, select {
    display: block;
    padding: 10px 6px;
    width: 100%;
    box-sizing: border-box;
    border: none;
    border-bottom: 1px solid #ddd;
    color: #555;
}
</style>