# Asyst-CDP Guide (Public)

***

- Create Date: 07 Nov 2023
- Created By : Stephen Dharma

***

Asyst - CDP (Content Delivery Platform) project. This is the Asyst CDP (Content Delivery Platform) public guide for Garuda Indonesia implementation.

## Template Library

### Marketing Templates

[Marketing Templates](marketing_templates) are used to send bulk email campaign blast to multiple recipients, and typically must be customized for each campaign day.

Here are the recommended templates which can be inherited and used to create your new Email Campaigns:

1. GarudaMiles Templates:
    - Holiday Greetings Template [with Banner, Footer] ([20200731 - Selamat Hari Raya Idul Adha 1441 H](./marketing_templates/20200731%20-%20Selamat%20Hari%20Raya%20Idul%20Adha%201441%20H/v20200731.html)). User GA-NL.
    - Standard Announcement Template [with Header, Banner, Footer] ([20220730 - Ucapan Terima Kasih atas Donasi Miles COVID-19](./marketing_templates/20220730%20-%20Ucapan%20Terima%20Kasih%20atas%20Donasi%20Miles%20COVID-19/v20200730.html)). User: GA-NL.
    - GA Travel Fair Template [with Header, Footer, no Banner] ([20230928 - Choose your favorite destination in Garuda Indonesia Online Travel Fair 2023](./marketing_templates/20230928%20-%20Choose%20your%20favorite%20destination%20in%20Garuda%20Indonesia%20Online%20Travel%20Fair%202023/v20230928.html)). User: GA-NL.
    - Mileage Expiry Information [with Banner] ([20231006 - Upcoming Expiry Miles](./marketing_templates/20231006%20-%20Upcoming%20Expiry%20Miles/v20231006.html)). User: GA-NL.
    - GA Travel Fair Template 2 [with Banner] ([20231020 - Garuda Indonesia Travel Fair 2023 Hadir Kembali](./marketing_templates/20231020%20-%20Garuda%20Indonesia%20Travel%20Fair%202023%20Hadir%20Kembali/v20231020.html)). User: GA-NL.
    - GarudaMiles CTA Template [Banner, ID/EN] ([20231025 - Tukar Poin Bank Jadi Miles Untuk Jelajahi Dunia Tanpa Batas](./marketing_templates/20231025%20-%20Tukar%20Poin%20Bank%20Jadi%20Miles%20Untuk%20Jelajahi%20Dunia%20Tanpa%20Batas/v20231025.html)). User: GA-NL.

2. Generic Public Customer Templates:
    - (empty)

### Transactional Templates

[Transactional Templates](./transactional_templates/) are used to send event-driven transactional emails (e.g. Booking Confirmation, Payment Confirmation, Ticketing Confirmation, Forgot Password, User Registration Confirmation, Point Accrual, Point Exchange, etc.).

1. Generic Public Customer Templates:
    - CX - Passenger Post-Flight Survey Template ([20231006 - CX - Passenger Post-Flight Survey](./transactional_templates/20231006%20-%20CX%20-%20Passenger%20Post-Flight%20Survey/v20231006.html)). User: GA-CX.

### Recipient Templates

[Recipient Templates](recipient_templates) are used to define bulk email recipient list. This template uses CSV (Comma-Separated Values) file format.

Here are the recommended templates which can be inherited and used to create your new Recipient List:

1. Marketing Recipient Templates:
    - GarudaMiles Recipient Template ([EDM_marketing_recipient_YYYYMMDD.csv](./recipient_templates/EDM_marketing_recipient_YYYYMMDD.csv)).
2. Transactional Recipieent Template:
    - CX - Passenger Post-Flight Survey Recipient Template ([EDM_pax_survey_YYYYMMDD.csv](./recipient_templates/EDM_pax_survey_YYYYMMDD.csv)).
