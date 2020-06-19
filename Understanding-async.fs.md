I am a truck truck driver currently, trying to 'get F#'. You are welcome to use it. I might post it in Dev.to if I get it worked out.  
  

## Understanding async (F#)

  
I am hungry for a Taco Bell chalupa, Wendy's baked potato and a Dairy Queen hot fudge shake. I happen to be at ["Iowa 80" - World's Largest Truckstop](https://iowa80truckstop.com/) All three restaurants are in their food court.  
  
**Synchronous programming:** I myself (being the main and single thread) go to Taco Bell and get my chalupa, then go to Wendy's and get by baked potato then hit DQ and get my shake and THEN sit down and enjoy my crazy meal.  
  
**Asynchronous:** I have five interns working for me. They are at my usage disposal. (they represent my thread pool) I ask the group for someone to get my chalupa at Taco Bell, Bob accepts and goes off to get it. Sam accepts the request from Wendy's for my potato and Alice accepts my shake request and goes to DQ for my shake. I sit down at a table.  
  
Doing this as  

>  Run.Synchronously

would be me waiting until all three return with the item they were assigned and then start eating all of them.  
  
Is this analogy on the right track?  
  
What would it be like to start eating any of the three items as soon as the intern delivers it to my table?  
  
How does the bang (!) work into this?  
  
Also, what about me playing on my phone while I sit at the table until someone returns?
