# Java - Receive a Message Tutorial

This project serves as a guide to help you build an application with FreeClimb. View this tutorial on [FreeClimb.com](https://docs.freeclimb.com/docs/how-to-receive-a-message#section-java). Specifically, the project will:

- Accepts incomming SMS messages and respond to them

## Setting up your new app within your FreeClimb account

To get started using a FreeClimb account, follow the instructions [here](https://docs.freeclimb.com/docs/getting-started-with-freeclimb).

## Setting up the Tutorial

1. Configure environment variables.

   | ENV VARIABLE            | DESCRIPTION                                                                                                                                                                        |
   | ----------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
   | ACCOUNT_ID   | Account ID which can be found under [API Keys](https://www.freeclimb.com/dashboard/portal/account/authentication) in Dashboard           |
   | AUTH_TOKEN   | Authentication Token which can be found under [API Keys](https://www.freeclimb.com/dashboard/portal/account/authentication) in Dashboard |
   | FREECLIMB_PHONE_NUMBER | The FreeClimb number that is being used to make a phone call. To learn more go [here](https://docs.freeclimb.com/docs/getting-started-with-freeclimb#section-2-get-a-phone-number) |
   | TO_PHONE_NUMBER         | The phone number which is being called. [Must be a verified phone number](https://docs.freeclimb.com/docs/using-your-trial-account#section-verifying-outbound-numbers) (for trial users) and in E.164 format.             |


## Building and Runnning the Tutorial

1. Build and run the application using command:

   ```bash
   $ gradle build && java -Dserver.port=3000 -jar build/libs/gs-spring-boot-0.1.0.jar
   ```

##Getting Help

If you are experiencing difficulties, [contact support](https://freeclimb.com/support).
