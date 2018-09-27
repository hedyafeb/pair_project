CROWD FUNDING:

Nama Database: galang_dana_db

Table: 
1. Project (input by admin)
    - PK: id: INTEGER
    - name: STRING
    - description
    - Amount needed
    - Current amount

2. Donator (input by donator)
    - id
    - userName
    - Name
    - password
    
3. Transaction (conjunction) (form)
    - id
    - ProjectId as FK
    - DonaturId as FK
    - Amount

List pages:
1. homepage (list project)
2. detail project (based on :ProjectId)
2. register
3. login 
4. logout
5. add Transaction (donation by donatur)
6. add Project cuma bisa ditambah manual dari admin
7. user profile ?? donasinya apa aja
8. Notification by email
10. approval pending/approved dari admin
11. admin page 
12. share by email +share to fb