Homework 7



Adding more functionality to the Volcano Coin contract



�. We made a payment mapping, but we havenʼt added all the functionality for it yet.
Write a function to view the payment records, specifying the user as an input.
What is the difference between doing this and making the mapping public ?


�. For the payments record mapping, create a function called recordPayment that
takes


�. the senderʼs address,


�. the receiverʼs address and


�. the amount
as an input, then creates a new payment record and adds the new record to the
userʼs payment record.



�. Each time we make a transfer of tokens, we should call the this recordPayment
function to record the transfer
