# Booking API Postman Collection
Welcome to the Booking API Postman Collection repository!

In this repository, you will find a Postman collection designed to interact with the Booking API. This collection covers a range of scenarios including both positive and negative test cases. The provided Postman collection and environment files enable comprehensive testing of the Booking API.

# Overview
The Postman collection in this repository includes:

Negative Scenarios: Tests designed to validate the API's response to incorrect or invalid inputs.

Positive Endpoints: Valid use cases for the Booking API to ensure proper functionality under expected conditions.

Additionally, there is a PDF document that provides a detailed demonstration of the work done with the Postman collection.

# Repository Structure
The repository is organized as follows:

collections/: Contains the Postman collection file (Booking API.postman_collection.json).

docs/: Contains a PDF document demonstrating the Postman collection and its use cases.

# Collection Details
# Negative Scenarios

1.Get Booking Details Invalid Id

Method: GET

URL: https://restful-booker.herokuapp.com/booking

Description: Attempts to get booking details with an invalid ID.

2.Create Booking Invalid Chars

Method: POST

URL: https://restful-booker.herokuapp.com/booking

Description: Attempts to create a booking with potentially invalid characters in the request body.

# Positive Endpoints

1.Get Booking Ids

Method: GET

URL: https://restful-booker.herokuapp.com/booking

Description: Retrieves a list of booking IDs.

2.Get Booking Details

Method: GET

URL: https://restful-booker.herokuapp.com/booking/3521

Description: Retrieves the details of a specific booking by ID.

3.Token Generator

Method: POST

URL: https://restful-booker.herokuapp.com/auth

Description: Generates a token for authentication purposes.

4.Update Booking

Method: PUT

URL: https://restful-booker.herokuapp.com/booking/313

Header:
Content-Type: application/json

Cookie: token=ee0e948353fd707

Description: Updates the details of an existing booking.

5.Delete Booking

Method: DELETE

URL: https://restful-booker.herokuapp.com/booking/313

Header:
Content-Type: application/json

Cookie: token=ee0e948353fd707

Description: Deletes a specific booking by ID.

5.Create Booking

Method: POST

URL: https://restful-booker.herokuapp.com/booking

Description: Creates a new booking with dynamic values for firstname and lastname.
