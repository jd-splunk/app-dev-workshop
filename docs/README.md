When working on the workshop, it is advised that you review your changes locally before committing them. The `mkdocs serve` command can be used to live preview your changes (as you type) on your local machine.

### Cloning the repo and installing dependancies
```bash
git clone https://github.com/signalfx/app-dev-workshop.git
cd ~/app-dev-workshop
sudo pip3 install -r requirements.txt
```

### Running the docs server
Use `0.0.0.0` for the IP address so it listens on all interfaces and define the port you want to listen on e.g. `8000`

```bash
mkdocs serve -a 0.0.0.0:8000
```

After these commands, the current branch is accessible through your favorite browser at <http://localhost:8000>
