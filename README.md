POJOQueries
===========

When you want to validate or enhance set of fields in a Plain Old Java Object, POJOQueries provides a out of the box solution with simplifying operations using simple queries. 

>boolean result = new POJOQuery<>().from(event).with("actor").eq("abc").with("action").eq("cde").evaluate();
