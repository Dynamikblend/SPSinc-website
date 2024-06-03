document.getElementById('donation-form').addEventListener('submit', function(e) {
    e.preventDefault();
    const amount = document.getElementById('amount').value;
    const certificate = `
        <h3>Thank You!</h3>
        <p>We appreciate your donation of $${amount}. Here is your certificate for tax purposes:</p>
        <p><strong>Nonprofit Organization</strong></p>
        <p>Donation Amount: $${amount}</p>
        <p>Date: ${new Date().toLocaleDateString()}</p>
    `;
    document.getElementById('certificate').innerHTML = certificate;
});