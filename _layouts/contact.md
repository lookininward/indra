{% include header.md %}

<div class="container mt-5">
  <div class="">
    <div class="prompt-header">
      Contact
    </div>

    <form
      action="https://formspree.io/vinoth.michaelxavier@gmail.com"
      method="POST"
      class="form form--contact"
    >

      <div class="form-group">
        <label for="name">Name</label>
        <input
          type="text"
          name="name"
          class="form-control"
        >
      </div>

      <div class="form-group">
        <label for="_replyto">Email</label>
        <input
          type="email"
          name="_replyto"
          class="form-control"
          required
        >
      </div>

      <div class="form-group">
        <label for="message">Message</label>
        <textarea
          name="message"
          rows="5"
          class="form-control"
          required
        >
        </textarea>
      </div>

      <input
        type="submit"
        value="Send"
        class="btn btn-primary"
      >
      <p class="mt-4">
        Your information will never be shared with third parties.
      </p>
    </form>
  </div>
</div>

{% include footer.md %}
