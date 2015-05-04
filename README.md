# Hibernate-Custom-Transformer

So AliasToBeanResultTransformer only transforms main object as entity but it doesn't have the 3
capability to select nested object as nested object. To get nested object, we should use Custom Transformer.
We will have something like below:

.setResultTransformer(new CustomTransformer(Example.class));
