# Ansible--roles-et-galaxy

# structure

mkdir deploy_phpmyadmin && cd deploy_phpmyadmin

mkdir -p roles/database/{tasks,defaults}
mkdir -p roles/phpmyadmin/{tasks,defaults}
touch inventory deploy_pma.yml
touch roles/database/tasks/main.yml roles/database/defaults/main.yml
touch roles/phpmyadmin/tasks/main.yml roles/phpmyadmin/defaults/main.yml

deploy_phpmyadmin/
├── inventory
├── deploy_pma.yml
├── roles/
│   ├── database/
│   │   ├── tasks/main.yml
│   │   └── defaults/main.yml
│   └── phpmyadmin/
│       ├── tasks/main.yml
│       └── defaults/main.yml

