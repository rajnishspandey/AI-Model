# AI-Model (rajnishspandey)
Hey There, I am Rajnish Pandey. I have created my own model using ollama3.2 for learning purpose. I will update to enhance the responses.  This model is designed to act as a versatile and intelligent assistant, specializing in tasks like: Solving complex data engineering challenges Simplifying AI/ML workflows

# Create your own AI model with the help of existing AI models.
I will give the example of llama3.2.

1 - download llama3.2 from ollama portal or meta ai
>  https://www.llama.com/llama-downloads/
or
>  https://ollama.com/download

2 - run it in your local system after installing
```shell
ollama run llama3.2
```

3 - now run the collection given in postman if you don't have download it.
4 - now update the modelfile's system parameter as per your requirement.
5 - inside the collection Model folder run create request
6 - model will be cretaed and you can play around it.

to test it you can run the command in you terminal 
```shell
ollama run rajnishspandey
```
and ask questions and get the response accordingly

### now let's push the model to ollama

1 - create account in ollama
2 - find the public keys stored in your computer inside ollama's folder (it will get created when you download ollama)
3 - now copy the public key to ollama
4 - in command prompt run
```shell
ollama cp rajnishspandey rajnishspandey/rajnishspandey
```
here it's

to test it you can run the command in you terminal 
```shell
ollama run rajnishspandey/rajnishspandey
```
and ask questions and get the response accordingly

ollama cp (to copy) rajnishspandey<ollama user name>/rajnishspandey<model name>

after this copy will get created

now 

run below command to push the model to ollama
```shell
ollama push rajnishspandey/rajnishspandey
```

![image](https://github.com/user-attachments/assets/a326f148-473c-4196-acc8-92a6e5fdf135)


check the model on ollama

https://ollama.com/rajnishspandey/rajnishspandey


to know more you can check the official documentation.
https://github.com/ollama/ollama/blob/main/docs/import.md
