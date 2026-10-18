<script> // state raw

  let firstName = $state.raw('');
  let lastName = $state.raw('');

  let person = $state.raw({
    firstName: 'User!',
    lastName: '',
  });

  function sayHello() {
    if (firstName && lastName) {
      person = {
        firstName: firstName,
        lastName: lastName,
      }
    }
  }
</script>

<div>
    <input type="text" bind:value={firstName} placeholder="First Name"> <br>
    <input type="text" bind:value={lastName} placeholder="Last Name"> <br>

    <button onclick={sayHello} >Say Hello</button>

    <h1>Hello {person.firstName} {person.lastName}</h1>
</div>
