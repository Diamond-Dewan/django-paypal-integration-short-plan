# Django PayPal Integration Short Plan

## Requirements analysis

PayPal provides a worldwide payment system. More and more business houses and implementing PayPay payment services for performing commercial transactions over the web. it is reasonable to say that the PayPay payment method on business websites is becoming a common option.  

The requirement of this project is develop a general payment system where customers can make an instant payment through PayPal. I will use Django-REST-Framework to integrate the PayPal payment system.

## Project design

1. **Properties:**
    1. PayPal token to make an order. 
    2. Database to save payment information.
2. **Methods:**
    1. Get PayPal client_id and secret_id then request for a token.
    2. Get customer order items price and make an order using token.
    3. Save the order information in the database.
    4. Give the checkout link to the customer. 
    5. Get checkout confirmation status and proceed to the delivery process.
    6. Refund for a certain case.
3. **Pre-Alpha** - Project demo: https://github.com/Diamond-Dewan/django-paypal

## Implementation

In this stage, I will develop methods and test individually one by one, based on design properties and methods.
1. **Versions**
    1. _Alpha_ - Write the primary logic of methods.
    2. _Beta_ - Recheck and write each method in terms of security and useability.
    3. _Preview_ - Release a preview state for practical usage and collect feedbacks.

## Testing (or Validation)

Test the application to check every component is working as expected way. Identify the bugs of the code and make changes as necessary to meet the design requirements.

Release a candidate version based on bug fixed.

## Documenting

**Internal Documentation:**

Documenting the internal design of software how each method works and the specific purpose they fulfill. This is a complete code specification to make upgrades and troubleshoot bugs that were missed in the initial testing phase.

**User Documentation:**

Manuals for End Users specify how each task of the application can be accomplished. This documentation will increase the useability of the application and save technical support from the trouble of answering basic questions.
    
**Final Release:** 

This is the final version(i.e: Version 1.0) of the project with proper documentation.

## Deployment

After the successful test, approved for release, and distributed into the production environment for end-users. 

## Maintenance

It takes valuable time and effort, as missed requirements may force the redesign of the software.
1. **Additional Release** - As Version 1.0 will not be the last release. Maintaining and enhancing is required to cope with newly discovered faults or requirements. 

|            Task              |      Time       |
| ---------------------------- |-----------------|
| Scope identification         |                4|
| Requirements Analysis        |                5|
| Design                       |                5|
| Pre-Alpha                    |                5|
| Development                  |               25|
| Alpha                        |                6|
| Beta                         |               10|
| Preview Release              |                7|
| Testing                      |                8|
| Release Candidate            |                6|
| Documentation                |               10|
| Final Release                |                5|
| Installation and deployment  |                2|
| Maintenance                  |               10|
| Additional Release           |               12|
| **DURATION**                 |   **120 days**  |
