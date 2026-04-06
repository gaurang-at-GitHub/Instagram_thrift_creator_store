I have created the ER diagram of the Instagram thrift creator store.
Here we are bhaving two categories which we have named as thrift and handmade, which we have classified under the entity product_type in ER diagram.
So the flow goes like this - firstly we have products entity which is having its own id as well as product_typeId, this product_typeId is linked to product_type entity.
the product_type entity is lined to thrift and handmade entity.
So basically thrift's product_type_id and handmade's product_type_id is linked to the product_type entity's id field, this can be the most confusing part, look carefully in the picture. You may get confused bcz of the lines not joining exact field in a particular entity cuz eraser does not supports that easily, i am more well versed with diagramdot db , next time i will be drawing it in there.
once the thrift and handmade entities are clear , we are having cart, order, payments entitties which have user item and the cart item entity that is bridging the business requirement.
User entity is connected address and cart, order, payment.
For tracking we have track entity connected to order entity.
You can see all the relationships that entities are having with each other in the screenshot.(i will be using diagram.db next time as i am not comfortable with eraser, if it looks complicated)

I have shared the code text file as code-export.. named as. First i wrote the commented things that helped me to understand which  entitites are all required and the field types as well as field properties vague overview. I am sharing what i wrote in one go.
