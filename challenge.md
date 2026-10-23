# Challenge: Install It Yourself

1. htop shows CPU and memory usage and the list of running processes.
   Command: sudo apt install -y htop, then htop

2. Ubuntu offers apache2 version 2.4.66-2ubuntu2.6.
   Command: apt show apache2 | head -3

3. 741 packages are installed.
   Command: apt list --installed | wc -l

4. The alpine container printed Hello from Alpine.
   Command: sudo docker run --rm alpine echo "Hello from Alpine"

5. Docker key: /etc/apt/keyrings/docker.asc
   Docker sources file: /etc/apt/sources.list.d/docker.sources

6. htop is removed; running htop now says command not found.
   Commands: sudo apt remove -y htop, hash -r, htop
