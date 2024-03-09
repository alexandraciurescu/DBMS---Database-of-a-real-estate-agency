# Managing the Database of a Real Estate Agency

The real estate agency's information system was designed to provide the agency's staff with an efficient tool for managing and accessing information about real estate properties and clients of the agency. The application uses a database to manage the listings and requests presented, as well as to record the contracts and transactions concluded.

The main utility of the application lies in the efficient storage of the information necessary for any agency of this type and quick access to it. Real estate agents can quickly find details about any property or contract they are dealing with through simple queries. Additionally, they can display suitable requests for an offer, suitable offers for a request, existing offers for each county and locality, the number of contracts concluded over a specified period, and more.

Therefore, the monitoring activities include:

1. **User Management (Employees):**
   - Storing employees' personal data (code, name, surname, ID number, education, position, address, phone, email).
   - Storing login credentials for application access (username and password).

2. **Client Management:**
   - Storing clients' personal information (code, name, surname, ID number, address, phone, email).

3. **Management of Requests and Offers:**
   - For each request/offer, storing the owner's data (client code) and main characteristics: property code, type of operation (buy/sell/rent), type of property (house, apartment, land), address, area, year of construction, budget/price, property description, etc.

4. **Management of Contracts and Concluded Transactions:**
   - For each client, creating a contract containing details such as contract number, agent code, client code, contract date, and commission.
   - For each concluded transaction, recording details such as transaction code, date, agent code, client codes for the seller and buyer, offer code, request code, amount paid, and commissions charged for the seller and buyer.
