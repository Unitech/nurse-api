# Nurse API 

Nurse API is a sandboxing solution.

## Bridge API

The API bridge uses Node.js, Express.

To lauch the api :

    node app.js
    
To access to the documentation go to http://localhost:3005/

![Nurse API](http://desmond.imageshack.us/Himg337/scaled.php?server=337&filename=nurseapicompileyourcode.png&res=medium)

### Unit testing 

    node test/api-test.js
    
## seccomp-nurse

Seccomp nurse is an Advanced Sandboxing Solution. It uses the Unix syscall **Seccomp** to jail entirely a process.

# Todo

- Handle compiled language (need to generate different out file)
- Better Doc
- Integrate seccomp-nurse

