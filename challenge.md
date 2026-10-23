# Challenge

1. Install http, run it.
Command: sudo apt install -y httpie
Run: http

2. Which version of apache2 does Ubuntu offer? (Do NOT install)
Command: apt show apache2

3. How many packages are installed?
Command: apt list --installed | wc -l

4. Run alpine and print Hello from Alpine.
Command: sudo docker run --rm alpine echo "Hello from Alpine"

5. Full path of Docker's key file, and sources file.
Key file: /etc/apt/keyrings/docker.asc
Sources file: /etc/apt/sources.list.d/docker.sources

6. Remove http and prove it is gone.
Command: sudo apt remove -y httpie
Command: hash -r
Command: http
