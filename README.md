# script
document.getElementById("ticket-form").addEventListener("submit", function(event) {
  event.preventDefault();

  const eventName = document.getElementById("event").value;
  const quantity = document.getElementById("quantity").value;

  const confirmationMessage = `You have successfully booked ${quantity} ticket(s) for the ${eventName}.`;

  document.getElementById("confirmation-message").innerText = confirmationMessage;
});

