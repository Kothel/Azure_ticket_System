# Azure_ticket_System


# <h1>Azure Ticket System Lab
  
  
## <a>Walkthrough </b>
###  1. First create honeypot VM
  - ![image](https://github.com/user-attachments/assets/9ccf1de9-4e13-4f3c-a5ae-de59a1a1501e)
  - download Azure OS Ticket System
  - ![image](https://github.com/user-attachments/assets/8cb1d286-70c4-4ef4-9a23-9004c082b0cb)
  - enable internet information services cgi
  - ![image](https://github.com/user-attachments/assets/662f921c-3c4b-471a-a5fd-40b0c72b20a3)
    

###  2. Download apps for Vm
  - access internet information service through loopback address
  - ![image](https://github.com/user-attachments/assets/d8d48acf-5616-40bf-9ed4-9f45cbc3ef4b)
  - downlaod php manager
  - ![image](https://github.com/user-attachments/assets/9a4f8916-9cb7-4bcf-a146-7ccad4a32275)
  - download rewrite module
  - ![image](https://github.com/user-attachments/assets/9d869ad3-105e-4093-95cb-44a040152ec6)
  - create php file
  - ![image](https://github.com/user-attachments/assets/a4dffefb-0de3-4c26-9d41-be7fae610712)
  - install visual C
  - ![image](https://github.com/user-attachments/assets/316e4588-8734-40e7-971c-8e120682caa8)
  - install mysql
  - ![image](https://github.com/user-attachments/assets/921aac5e-5584-41a2-9665-6cbd28cf8e6b)
    ![image](https://github.com/user-attachments/assets/d5717ab6-b2ad-4735-ad95-0310a75da644)
  - move osTicket to wwwroot
  - ![image](https://github.com/user-attachments/assets/76d6bd4f-8bf9-48c6-a227-dcf9b71cde4f)
  - install heidsql
  - ![image](https://github.com/user-attachments/assets/c9e48ab5-5ca2-47a1-a581-02c3792c87d0)


###  3. PHP manage
  - open php manager in IIS
  - ![image](https://github.com/user-attachments/assets/65603816-dc03-4ee8-9436-25da69e77b27)
  - go to osticket installer from iis manager
  - ![image](https://github.com/user-attachments/assets/b5c5b50f-ac5d-46cf-8cf3-7d1ede305496)
  - enable imap intl and opcache dll in php extensions
  - ![image](https://github.com/user-attachments/assets/9f7c389b-96eb-4531-8152-d9091fbd39bf)


  ### 4. osTicket installtion
  - change pemissions of ostconfig in osticket folder
  - ![image](https://github.com/user-attachments/assets/29ee7d37-894f-49f8-8df8-152d188f022d)
  - install osTicket
  - ![image](https://github.com/user-attachments/assets/cf448293-19c8-423f-a0d7-78bc08d1e79a)
  - install HeidSQL
  - ![image](https://github.com/user-attachments/assets/6a9d15e8-7fa6-457b-8cd1-0657fe98e9df)
  - login
  - ![image](https://github.com/user-attachments/assets/2bdbbcd2-8248-4d14-942a-50daae890881)


  ### 4. osTicket setup
  - add master admin role department and team
  - ![image](https://github.com/user-attachments/assets/ff84b01a-57f7-492a-8505-4d204b360b76)
    ![image](https://github.com/user-attachments/assets/4e251409-549f-4726-8518-52787193cd21)
    ![image](https://github.com/user-attachments/assets/f3e3413d-0e5d-4baf-9669-1aee91e8bb8e)
  - add agents and users
  - ![image](https://github.com/user-attachments/assets/d9c0fc0f-3939-4061-a700-dd6602b87531)
    ![image](https://github.com/user-attachments/assets/45be1ea0-3bf5-41e9-9b76-502b17e28332)
  - add SLA plans
  - ![image](https://github.com/user-attachments/assets/f1c2568e-0d12-41b7-aca7-f44d0848ef8c)
  - add help topics
  - ![image](https://github.com/user-attachments/assets/66c9b991-b8d3-4ece-a2c3-b3038520c4e2)


 ### 5. Simulate tickets
  - create a few tickets
  - ![image](https://github.com/user-attachments/assets/ddcac0b2-2d8c-450d-a479-d249e469ae91)
    ![image](https://github.com/user-attachments/assets/e2cfec1e-fa0e-43f3-8d48-8c38ce5ced52)
    ![image](https://github.com/user-attachments/assets/c003437a-e9be-47df-a7c1-1de2d03f0d47)
  - login as a support agent to view tickets
  - ![image](https://github.com/user-attachments/assets/4b1ae2f0-516e-4b10-a005-7c1de7e65fe5)

  - categorize first ticket as a support agent
  - ![image](https://github.com/user-attachments/assets/728e8fa1-b0c2-4102-b901-3d830211e4f6)
    ![image](https://github.com/user-attachments/assets/a0bfd781-911e-45e1-8a18-35cdf48c1ef3)
    ![image](https://github.com/user-attachments/assets/35eb7a7e-ecff-41be-aa7a-f4f904839fde)

  - Ticket 2
  - ![image](https://github.com/user-attachments/assets/4fb5f11a-01ff-420e-b68e-8957b649e81d)
    ![image](https://github.com/user-attachments/assets/85d83f86-67f1-4390-aea0-311fd267eeb7)
    ![image](https://github.com/user-attachments/assets/29683185-7be0-4ee5-b2be-0f56e6d53f07)
    ![image](https://github.com/user-attachments/assets/fc01d0fc-b195-4fa1-a089-40fe52faeab6)

  - ticket 3
  - ![image](https://github.com/user-attachments/assets/74ca3b80-169f-4d50-8236-fd106e2fd1fc)
    
  - all tickets closed
  - ![image](https://github.com/user-attachments/assets/0e6cd7b6-eaf2-4059-9b16-7bfa724c8c15)


# Azure_Ticket_system
