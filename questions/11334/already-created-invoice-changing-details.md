## Already created invoice, changing details

- posted by: [user3284463](https://stackexchange.com/users/3982995/user3284463) on 2016-10-13
- tagged: `tech-company`, `legal`, `sales`
- score: 1

<p>I have a website that auto-generates invoices depending on the users address and name. </p>

<p>At the moment what I have is if the user changes his address or name, the invoice that were previously created would also be updated. </p>

<p>Is this OK, or is there another way around it?</p>



## Answer 11337

- posted by: [Neil](https://stackexchange.com/users/2711480/neil) on 2016-10-13
- score: 4

<p>I would say it better to have the actual historical invoices preserved as they have been sent to clients/customers. There are lots of auto-matching software that may identify issues, but also for a company's own records it is important to match what you have given to the customer. </p>



## Answer 11351

- posted by: [Jeremy Parsons](https://stackexchange.com/users/497810/jeremy-parsons) on 2016-10-14
- score: 2

<p>In jurisdictions I know, <strong>an invoice is a legal document and must not change</strong>. </p>

<p>On the other hand, it would be insane if you couldn't generate a <em>customer statement</em> that showed open and closed invoices and gave the current contact details.</p>

<p>It's urgent that you <strong>fix your invoice problem</strong>. The good news is that there's almost certainly a quick, straightforward and good enough answer for the short term, perhaps just generating and storing PDFs.</p>

<p>As a side-note, I've only once led a B2B business that did no invoicing. Our Terms and Conditions required customers to self-invoice. That had a very specific business reason related to a complex supply chain. It's unlikely that you're in an industry where this is the normal way of doing business.</p>



## Answer 11338

- posted by: [Mark D Wolinski](https://stackexchange.com/users/9304012/mark-d-wolinski) on 2016-10-13
- score: 0

<p>The bigger question here is how you're storing your data.  Is the invoice stored with the address information or is it just referenced to another table that has the customer data in it?</p>

<p>If you create an invoice, which is linked to the customer information, then if the customer updates their information, the invoice should reference the latest update.  But you would probably want to maintain a state history.</p>

<p>For example, Invoice is created for Customer A with Address A and sent to customer.  My customer table has basic information but the address is stored in a separate table with a start date/end date.  With this set-up, I can have a history that Customer A entered Address A on Jan 1.  Then on Jan 5 they changed it to Address B.</p>

<p>If you send the invoice to the customer, then when they change their address, you can offer them the option of receiving a new invoice with the updated information.</p>

<p>Either way, you should also have a history state table that shows when invoices were generated and with what information at that time.  For example, On Jan 1, Invoice 1 was generated for Customer A with Address A.  On Jan 5, Invoice 1 was updated for Customer A with Address B.  On Jan 6, Invoice 1 was paid by Customer A.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
