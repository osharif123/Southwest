# Southwest
Lol you really think I will spend the time filling out a README file? 

Actually, 
1. to build the container: `docker build -t southwest . `
2. To run the container `sudo docker run -it --privileged southwest Confirmation First Last`
3. To run a test and make sure things are working: `sudo docker run -it southwest pytest -v tests/unit tests/integration`