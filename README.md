# Titan_LLM

Google doc https://docs.google.com/document/d/17r1bUmduTgJ821spLmGmpsF--PjTYqBUEEV4X-Gn4vo/edit?usp=sharing

### Dependencies
- youtube-transcript-api: https://pypi.org/project/youtube-transcript-api/
- pyPDF2: https://pypi.org/project/PyPDF2/

### Environment Setup
To contribute to this project or clone it using SSH, follow these steps:

1. **Generate SSH Key**
    - Open your terminal (connect to your remote server if applicable)
    - Generate a new SSH key pair using the following command:
      ```bash
      ssh-keygen -t ed25519 -C "your_email@example.com"
      ```
        - `ssh-keygen` → Starts the SSH key generation process  
        - `-t ed25519` → Encryption algorithm  
        - `-C` → Identifying comment
    - When prompted, press **ENTER** to accept the default file location
    - (Optional) Enter a passphrase (can be left blank)

2. **Add Public Key to GitHub**
    - Display your public key using:
      ```bash
      cat ~/.ssh/id_ed25519.pub
      ```
    - Copy the entire line (starts with `ssh-ed25519` and ends with your email address) and paste it in GitHub:
        - **GitHub → Settings → SSH and GPG Keys → New SSH key → Paste it there**

3. **Clone the Repository via SSH**
    - On your GitHub repository page, click the **CODE** button
    - Select the **SSH** option and copy the provided URL
    - In your terminal, run:
      ```bash
      git clone <repository_SSH_URL>
      ```

4. Freely access and work with the repository.


### Training Data
- Textbook: Introduction_to_Python_Programming_-_WEB.pdf
- Youtube: Playlist ID: PL8DDJG7GRNac8Hf6NWtevdrGE1vkTL3oL

## To Do
- [x] gather adequate training data
- [ ] vectorize data
- [ ] train model
- [ ] Take a look at Flask for front end  (Also discussed VUE, svelt)
- [ ] go through demo 2 on http://github.com/cs50/ai-workshop
- [ ] go through demo 3 on http://github.com/cs50/ai-workshop
- [ ] Greg upload code to go from youtube playlistID to videoID
- [ ] Any documentation on failed youtube videoIDs figure out why
- [ ] Why the open stax textbook failed embeddings
- [ ] Codespaces?  How hard is it? Still free? Would this be a possibilty for an environment for COSC 1010?
- [ ] Could the Titan be a server for this project?
