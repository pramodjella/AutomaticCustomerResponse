# AutomaticCustomerResponse
Finetuning FlanT5 model for automatic customer support

Flan T5 model is finetuned by augmenting hugging face Kaludi/Customer-Support-Responses data with synthetic data from GPT-4o

Response of original model for Query: I was charged incorrectly is He has to be on the street. which is not relevant  at all.
while Lora Finetuned model is We'd be happy to help. Can you please provide more details about your question?. 

Although the response is not best, it is better than original model.
May be large dataset or already instruction finetuned model like GPT3.5 or 4 could give better results for the hugging face result.
Due to resource constraints couldn't able to use them.
