{% docs payment_status %}
One of the following values:

| status               | definition                                     |
| ---------------------|------------------------------------------------|
| success              |Order placed, not yet shipped                   |
| fail                 |Order has been shipped, not delivered           |
{% enddocs %}


{% docs payment_method %}
One of the following values:

| status               | definition                                     |
| ---------------------|------------------------------------------------|
| credit_card          | Applicable credit card brand                   |
| bank_transfer        | Yappy or direct fund wire                      |
| coupon               | Coupon from event                              |
| gift_card            | Applicable gift card from partners             |
{% enddocs %}