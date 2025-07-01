Use Case Examples – Airbnb Booking System
👤 Use Case: User Registration
Actor: Guest or Host
Description: A user signs up with a name, email, and password. Role (host/guest) is assigned.
Outcome: New user profile is created and saved in the database.

🔐 Use Case: Login and Authentication
Actor: Registered User
Description: User logs in using email/password or OAuth provider.
Outcome: User receives secure session token via JWT.

🏡 Use Case: Create Property Listing
Actor: Host
Description: Host adds a new property with details like location, price, amenities, and photos.
Outcome: Property is saved and associated with the host’s profile.

🔍 Use Case: Search Properties
Actor: Guest
Description: Guest searches listings using filters (location, price range, amenities).
Outcome: Matching properties are displayed.

📅 Use Case: Book a Property
Actor: Guest
Description: Guest selects dates and books an available property.
Outcome: A new booking record is created with a pending status.

❌ Use Case: Cancel Booking
Actor: Guest or Host
Description: User cancels an existing booking.
Outcome: Booking status updated to “canceled” with refund rules applied.

💳 Use Case: Make Payment
Actor: Guest
Description: Guest completes payment using a chosen method (credit card, PayPal, etc.).
Outcome: Payment record stored; funds processed.

⭐ Use Case: Leave a Review
Actor: Guest
Description: After a stay, the guest submits a rating and comment.
Outcome: Review linked to property and booking is saved.

💬 Use Case: Message Host
Actor: Guest
Description: Guest sends a message to a host for inquiries.
Outcome: Message recorded in the system and delivered to host.

🧑‍💻 Use Case: Admin Manages Users
Actor: Admin
Description: Admin reviews users and manages listings, bookings, or content.
Outcome: Administrative changes are logged and applied.
