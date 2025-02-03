# amazon-Marketing_Campaign_Success
Este caso foi apresentado em um processo de admissão de analista de dados na Amazon. Esta é minha resolução.

https://platform.stratascratch.com/coding/514-marketing-campaign-success-advanced?code_type=5

You have a table of in-app purchases by user. Users that make their first in-app purchase are placed in a marketing campaign where they see call-to-actions for more in-app purchases. Find the number of users that made additional in-app purchases due to the success of the marketing campaign.


The marketing campaign doesn't start until one day after the initial in-app purchase so users that only made one or multiple purchases on the first day do not count, nor do we count users that over time purchase only the products they purchased on the first day.

Table: marketing_campaign


created_at:
datetime2
price:
bigint
product_id:
bigint
quantity:
bigint
user_id:
bigint
