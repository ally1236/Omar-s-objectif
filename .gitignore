<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Activation Code</title>
    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <!-- CSS -->
    <style>
        body {
            font-family: Arial, sans-serif;
        }

        #activation-code {
            background-color: #f7f7f7;
            padding: 40px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body>
    <!-- Activation Code Section -->
    <section id="activation-code" class="container mt-5">
        <div class="row justify-content-center">
            <div class="col-md-6">
                <h2>Activation Code</h2>
                <form id="activationCodeForm">
                    <div class="form-group">
                        <label for="email">Email:</label>
                        <input type="email" class="form-control" id="email" placeholder="Enter your email" required>
                    </div>
                    <button type="submit" class="btn btn-primary w-100">Send Activation Code</button>
                </form>
            </div>
        </div>
    </section>

    <!-- Bootstrap & jQuery JS -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
    <!-- EmailJS -->
    <script src="https://cdn.emailjs.com/dist/email.min.js"></script>
    <script>
        $(document).ready(function() {
            $('#activationCodeForm').submit(function(e) {
                e.preventDefault();
                var email = $('#email').val();
                if (email === 'muhozaomar099@gmail.com') {
                    // Send email using EmailJS
                    emailjs.send('service_kg2s087', 'template_ck61hc2', { email: email })
                        .then(function(response) {
                            alert('Activation code sent to ' + email);
                        }, function(error) {
                            console.log('Error sending email:', error);
                            alert('Error sending email. Please try again later.');
                        });
                } else {
                    alert('Invalid email. Please enter a valid email address.');
                }
            });
        });
    </script>
</body>
</html>