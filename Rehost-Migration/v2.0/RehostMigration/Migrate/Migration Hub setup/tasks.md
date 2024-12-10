
# Module: Migration Hub setup
## Task 1: Set up home region in Migration Hub console
#### Description
Set up your home region in Migration Hub console. 

To choose your home Region using the console

1. Using your AWS account, sign in to the AWS Management Console and open the [Migration Hub console](https://console.aws.amazon.com/migrationhub/)
2. In the lower-section of the Migration Hub console navigation pane, choose Settings.
3. Under Migration Home Region, select your home Region.
4. Optionally, you can enable the console to automatically switch to your home Region the next time you sign in to the AWS Management Console.
5. Choose Confirm Home Region to set the home Region.

For more details, see [Choose an AWS Migration Hub home Region](https://docs.aws.amazon.com/migrationhub/latest/ug/select-home-region.html).
## Task 2: Account connection setup
#### Description
To create an AWS account connection, you first initiate a connection request in the Migration Hub Journeys console. The next step is for an administrator of the AWS account to accept the connection request.

To initiate an account connection request

1. Go to the Account connections tab in this journey.
2. Choose Connect account.
3. For Connection name enter a name that can help you and other journey members identify this connection.
4. For AWS account ID enter the ID of the AWS account to which you want to connect the journey. An AWS account ID is a 12-digit number.
5. (Optional) Enter a description for this new connection.
6. Choose Initiate account connection.
7. Copy the connection ARN. You need this ARN to complete the account connection.

To accept a connection request

1. Sign in to the [AWS Management Console](https://console.aws.amazon.com/) and open the [Migration Hub console](https://console.aws.amazon.com/migrationhub/).
2. In the left navigation pane, choose Journey connections.
3. Choose Verify new connection.
4. Enter the connection ARN that Migration Hub Journeys generated when the connection request was initiated.
5. Choose Accept connection.

## Task 3: Create and associate IAM/Journey role
#### Description
After you create an AWS account connection, associate IAM roles with it so that the journey that has the connection can use these roles to create and update AWS resources as needed by the tasks of the journey.

To associate IAM roles with an account connection

1. Go to the Account connections tab in this journey.
2. Choose the name of the connection with which you want to associate IAM roles. The connection page opens.
3. Choose Associate roles with connection. The connection page opens in the [AWS Migration Hub console](https://console.aws.amazon.com/migrationhub/).
4. In the connection page in the [AWS Migration Hub console](https://console.aws.amazon.com/migrationhub/), choose Create and associate roles with journey.
5. Review the list of roles, and then choose Create and associate roles.

For more details, see [Associating roles with an account connection](https://docs.aws.amazon.com/mhj/latest/userguide/associate-roles.html).