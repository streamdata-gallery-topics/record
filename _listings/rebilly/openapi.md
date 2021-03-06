swagger: "2.0"
x-collection-name: Rebilly
x-complete: 1
info:
  title: Rebilly
  description: -introductionthe-rebilly-api-is-built-on-http---our-api-is-restful---it-has-predictableresource-urls---it-returns-http-response-codes-to-indicate-errors---it-alsoaccepts-and-returns-json-in-the-http-body---you-can-use-your-favoritehttprest-library-for-your-programming-language-to-use-rebillys-api-oryou-can-use-one-of-our-sdks-currently-available-in-phphttpsgithub-comrebillyrebillyphpand-chttpsgithub-comrebillyrebillydotnetclient--authenticationwhen-you-sign-up-for-an-account-you-are-given-your-first-api-key-you-can-generate-additional-api-keys-and-delete-api-keys-as-you-mayneed-to-rotate-your-keys-in-the-future--you-authenticate-to-therebilly-api-by-providing-your-secret-key-in-the-request-header-rebilly-offers-three-forms-of-authentication--private-key-json-web-tokens-andpublic-key--private-key-authenticates-each-request-by-searching-for-the-presenceof-an-http-header-rebapikey--jwt-authenticates-each-request-by-the-http-header-authorization--public-key-authenticates-by-the-http-header-rebauth-read-more-on-this-below-rebilly-also-offers-json-web-tokens-jwt-authentication-where-you-can-controlthe-specific-granular-permissions-and-expiration-for-that-jwt---we-call-our-resourcefor-generating-jwt-sessionstagsessions-rebilly-also-has-a-clientside-authentication-scheme-that-uses-anapiuser-and-hmacsha1-signature-only-for-the-tokens-resource-sothat-you-may-safely-create-tokens-from-the-clientside-without-compromisingyour-secret-keys-never-share-your-secret-keys--keep-them-guarded-and-secure-the-clientside-authentication-scheme-uses-one-http-header-named-rebauth--redocinject-securitydefinitions--php-sdkfor-all-php-sdk-examples-provided-in-this-spec-you-will-need-to-configure-client-you-may-do-it-like-thisphpclient--new-rebillyclient----apikey--yourapikeyhere----baseurl--httpsapi-rebilly-com
  termsOfService: https://www.rebilly.com/terms/
  contact:
    name: Rebilly API Support
    url: https://www.rebilly.com/contact/
    email: integrations@rebilly.com
  version: "2.1"
host: api.rebilly.com
basePath: /v2.1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /files/{id}:
    get:
      summary: Retrieve a File Record
      description: Retrieve a File with specified identifier string
      operationId: files.id.get
      x-api-path-slug: filesid-get
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - File
      - Record
  /custom-events/{id}/rules/history/{version}:
    get:
      summary: Retrieve the record from the change history of the set of rules for
        a custom event
      description: |-
        Retrieve the record from the change history of the set of rules for the selected custom event.
        A history record is created each time you change the rules.
      operationId: retrieve-the-record-from-the-change-history-of-the-set-of-rules-for-the-selected-custom-event-a-hist
      x-api-path-slug: customeventsidruleshistoryversion-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Record
      - From
      - Change
      - History
      - Of
      - Set
      - Of
      - Rulesa
      - Custom
      - Event
  /events/{eventType}/rules/history/{version}:
    get:
      summary: Retrieve the record from the change history of the set of rules
      description: |-
        Retrieve the record from the change history of the selected set of rules.
        A history record is created each time you change the rules.
      operationId: retrieve-the-record-from-the-change-history-of-the-selected-set-of-rules-a-history-record-is-created
      x-api-path-slug: eventseventtyperuleshistoryversion-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Record
      - From
      - Change
      - History
      - Of
      - Set
      - Of
      - Rules