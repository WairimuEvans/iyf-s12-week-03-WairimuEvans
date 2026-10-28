# Terminal Log — Week 3

## Task 5.1: Navigation and Directory Structure
- `pwd`
- `cd ~/Documents`
- `cd ..`
- `cd ~`
- `mkdir -p my-project/src/css my-project/src/js my-project/src/images my-project/docs my-project/tests`
- `touch my-project/README.md`
- `find my-project`

## Task 5.2: File and Directory Operations
- `touch index.html`
- `cat index.html`
- `cp index.html backup.html`
- `mv backup.html ~/my-project/docs/`
- `mv index.html home.html`
- `rm home.html`
- `mkdir -p src/css`
- `cp -r src src-backup`
- `mkdir -p archive`
- `mv src-backup archive/`
- `rm -r src`
- `rm -r archive`

## Task 5.3: Finding and Inspecting Files
- `find . -type f -name "*.html" | wc -l`
- `grep -ril "contact" --include="*.html" .`
- `find . -type f -name "*.css"`
- `wc -l` — used to count CSS lines
- `history | tail -10`

## Task 5.4: Bash Script
- `touch new-project.sh`
- `code new-project.sh`
- `chmod +x ~/iyf-s12-week-03-WairimuEvans/new-project.sh`
- `bash ~/iyf-s12-week-03-WairimuEvans/new-project.sh`
- `bash ~/iyf-s12-week-03-WairimuEvans/new-project.sh my-awesome-app`
- `find my-awesome-app`
