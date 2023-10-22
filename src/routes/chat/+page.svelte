<h1>StableHorde AI Bot Chat Feature</h1>

<form class="form">
	<div class="form-input">
		<label for="prompt">Input your prompt: </label>
		<textarea id="input-textarea" name="prompt" rows="10" cols="33" />
	</div>
	<button class="form-submit btn" type="submit"> Submit </button>
</form>

<style>
	.form-input {
		display: flex;
		flex-direction: column;
		row-gap: 1rem;
	}

	.form-submit {
		margin-top: 1.5rem;
		font-size: 1.25rem;
	}

	.form-input > label {
		font-size: 1.5rem;
	}
</style>
