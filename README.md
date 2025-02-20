<?php
/*
Template Name: Airline Booking
*/
get_header(); ?>

<main id="site-content">
    <div class="booking-form-container">
        <h1>Airline Booking Form</h1>
        <form id="airline-booking-form" method="post">
            <!-- Flight Search Fields -->
            <label for="departure">Departure City:</label>
            <input type="text" id="departure" name="departure" required>

            <label for="destination">Destination City:</label>
            <input type="text" id="destination" name="destination" required>

            <label for="departure-date">Departure Date:</label>
            <input type="date" id="departure-date" name="departure-date" required>

            <label for="return-date">Return Date:</label>
            <input type="date" id="return-date" name="return-date">

            <label for="passengers">Passengers:</label>
            <select id="passengers" name="passengers">
                <option value="1">1 Adult</option>
                <option value="2">2 Adults</option>
                <option value="3">3 Adults</option>
                <option value="4">4 Adults</option>
            </select>

            <!-- Passenger Details -->
            <label for="full-name">Full Name:</label>
            <input type="text" id="full-name" name="full-name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="phone">Phone:</label>
            <input type="tel" id="phone" name="phone" required>

            <!-- Payment Details -->
            <label for="card-number">Card Number:</label>
            <input type="text" id="card-number" name="card-number" required>

            <label for="expiry-date">Expiry Date:</label>
            <input type="month" id="expiry-date" name="expiry-date" required>

            <label for="cvv">CVV:</label>
            <input type="text" id="cvv" name="cvv" required>

            <button type="submit">Book Now</button>
        </form>
    </div>
</main>

<?php get_footer(); ?>
