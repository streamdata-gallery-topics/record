---
swagger: "2.0"
x-collection-name: 3dcart
x-complete: 0
info:
  title: 3dcart This method is used to update a single order record in the database.
    The {orderid} parameter specifies which order record to update.
  version: 1.0.0
  description: This method is used to update a single order record in the database.
    the {orderid} parameter specifies which order record to update..
host: apirest.3dcart.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /3dCartWebAPI/v1/Cart/{orderkey}:
    put:
      summary: This method is used to update a single cart record in the database.
        The {orderkey} parameter specifies which cart record to update.
      description: This method is used to update a single cart record in the database.
        the {orderkey} parameter specifies which cart record to update..
      operationId: Carts_Update
      x-api-path-slug: 3dcartwebapiv1cartorderkey-put
      parameters:
      - in: body
        name: cart
        description: A Json or XML object containing the cart
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: orderkey
        description: Order Key
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - This
      - Method
      - Is
      - Used
      - To
      - Update
      - Single
      - Cart
      - Record
      - In
      - Database
      - ""
      - Orderkey
      - Parameter
      - Specifies
      - Which
      - Cart
      - Record
      - To
      - Update
  /3dCartWebAPI/v1/Categories/{categoryid}:
    put:
      summary: This method is used to update a single category record in the database.
        The {categoryid} parameter specifies which category to update.
      description: This method is used to update a single category record in the database.
        the {categoryid} parameter specifies which category to update..
      operationId: Category_Update
      x-api-path-slug: 3dcartwebapiv1categoriescategoryid-put
      parameters:
      - in: body
        name: category
        description: A Json or XML object containing the new category
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: categoryid
        description: Category ID
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - This
      - Method
      - Is
      - Used
      - To
      - Update
      - Single
      - Category
      - Record
      - In
      - Database
      - ""
      - Categoryid
      - Parameter
      - Specifies
      - Which
      - Category
      - To
      - Update
  /3dCartWebAPI/v1/CRM/{id}:
    put:
      summary: This method is used to update a single CRM record in the database.
        The {id} parameter specifies which CRM record to update.
      description: This method is used to update a single crm record in the database.
        the {id} parameter specifies which crm record to update..
      operationId: CRM_UpdateCRM
      x-api-path-slug: 3dcartwebapiv1crmid-put
      parameters:
      - in: body
        name: crm
        description: A Json or XML object containing the new product
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: Crm ID
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - This
      - Method
      - Is
      - Used
      - To
      - Update
      - Single
      - CRM
      - Record
      - In
      - Database
      - ""
      - Id
      - Parameter
      - Specifies
      - Which
      - CRM
      - Record
      - To
      - Update
  /3dCartWebAPI/v1/CRM/department/{id}:
    put:
      summary: This method is used to update a single CRM Department record in the
        database. The {id} parameter specifies which CRM Department record to update.
      description: This method is used to update a single crm department record in
        the database. the {id} parameter specifies which crm department record to
        update..
      operationId: CRM_UpdateDepartment
      x-api-path-slug: 3dcartwebapiv1crmdepartmentid-put
      parameters:
      - in: body
        name: department
        description: A Json or XML object containing the new Department
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: Department ID
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - This
      - Method
      - Is
      - Used
      - To
      - Update
      - Single
      - CRM
      - Department
      - Record
      - In
      - Database
      - ""
      - Id
      - Parameter
      - Specifies
      - Which
      - CRM
      - Department
      - Record
      - To
      - Update
  /3dCartWebAPI/v1/CRM/savedreply/{id}:
    put:
      summary: This method is used to update a single CRM SavedReply record in the
        database. The {id} parameter specifies which CRM SavedReply record to update.
      description: This method is used to update a single crm savedreply record in
        the database. the {id} parameter specifies which crm savedreply record to
        update..
      operationId: CRM_UpdateSavedReply
      x-api-path-slug: 3dcartwebapiv1crmsavedreplyid-put
      parameters:
      - in: path
        name: id
        description: SavedReply ID
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: body
        name: savedreply
        description: A Json or XML object containing the new SavedReply
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - This
      - Method
      - Is
      - Used
      - To
      - Update
      - Single
      - CRM
      - SavedReply
      - Record
      - In
      - Database
      - ""
      - Id
      - Parameter
      - Specifies
      - Which
      - CRM
      - SavedReply
      - Record
      - To
      - Update
  /3dCartWebAPI/v1/CRM/status/{id}:
    put:
      summary: This method is used to update a single CRM Status record in the database.
        The {id} parameter specifies which CRM Status record to update.
      description: This method is used to update a single crm status record in the
        database. the {id} parameter specifies which crm status record to update..
      operationId: CRM_UpdateStatus
      x-api-path-slug: 3dcartwebapiv1crmstatusid-put
      parameters:
      - in: path
        name: id
        description: Status ID
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: body
        name: status
        description: A Json or XML object containing the new Status
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - This
      - Method
      - Is
      - Used
      - To
      - Update
      - Single
      - CRM
      - Status
      - Record
      - In
      - Database
      - ""
      - Id
      - Parameter
      - Specifies
      - Which
      - CRM
      - Status
      - Record
      - To
      - Update
  /3dCartWebAPI/v1/Customers/{customerid}:
    put:
      summary: This method is used to update a single customer record in the database.
        The {id} parameter specifies which customer record to update.
      description: This method is used to update a single customer record in the database.
        the {id} parameter specifies which customer record to update..
      operationId: Customers_Update
      x-api-path-slug: 3dcartwebapiv1customerscustomerid-put
      parameters:
      - in: body
        name: customer
        description: A Json or XML object containing the new customer
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: customerid
        description: Customer ID
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - This
      - Method
      - Is
      - Used
      - To
      - Update
      - Single
      - Customer
      - Record
      - In
      - Database
      - ""
      - Id
      - Parameter
      - Specifies
      - Which
      - Customer
      - Record
      - To
      - Update
  /3dCartWebAPI/v1/Distributors/{distributorid}:
    put:
      summary: This method is used to update a single distributor record in the database.
        The {distributorid} parameter specifies which distributor to update.
      description: This method is used to update a single distributor record in the
        database. the {distributorid} parameter specifies which distributor to update..
      operationId: Distributors_Update
      x-api-path-slug: 3dcartwebapiv1distributorsdistributorid-put
      parameters:
      - in: body
        name: distributor
        description: A Json or XML object containing the new distributor
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: distributorid
        description: Distributor ID
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - This
      - Method
      - Is
      - Used
      - To
      - Update
      - Single
      - Distributor
      - Record
      - In
      - Database
      - ""
      - Distributorid
      - Parameter
      - Specifies
      - Which
      - Distributor
      - To
      - Update
  /3dCartWebAPI/v1/Manufacturers/{manufacturerid}:
    put:
      summary: This method is used to update a single manufacturer record in the database.
        The {manufacturerid} parameter specifies which manufacturer record to update.
      description: This method is used to update a single manufacturer record in the
        database. the {manufacturerid} parameter specifies which manufacturer record
        to update..
      operationId: Manufacturer_Update
      x-api-path-slug: 3dcartwebapiv1manufacturersmanufacturerid-put
      parameters:
      - in: body
        name: manufacturer
        description: A Json or XML object containing the new manufacturer
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: manufacturerid
        description: Manufacturer ID
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - This
      - Method
      - Is
      - Used
      - To
      - Update
      - Single
      - Manufacturer
      - Record
      - In
      - Database
      - ""
      - Manufacturerid
      - Parameter
      - Specifies
      - Which
      - Manufacturer
      - Record
      - To
      - Update
  /3dCartWebAPI/v1/Orders/{orderid}:
    put:
      summary: This method is used to update a single order record in the database.
        The {orderid} parameter specifies which order record to update.
      description: This method is used to update a single order record in the database.
        the {orderid} parameter specifies which order record to update..
      operationId: Orders_Update
      x-api-path-slug: 3dcartwebapiv1ordersorderid-put
      parameters:
      - in: body
        name: order
        description: A Json or XML object containing the order
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: orderid
        description: OrderID
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - This
      - Method
      - Is
      - Used
      - To
      - Update
      - Single
      - Order
      - Record
      - In
      - Database
      - ""
      - Orderid
      - Parameter
      - Specifies
      - Which
      - Order
      - Record
      - To
      - Update
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---