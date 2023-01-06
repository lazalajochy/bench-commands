# bench-commands

# start a new proyect 
bench init [name-proyect] --frappe-branch version-13  (or new version)

# create a new site
bench new-site [side-name]

note: if you run the proyect and you receibe an error side not found, that is because the currentsite.txt file was not created it, please follow thise steps
if you are using using ubunto

1---> sudo touch currentsite.txt

2---> sudo nano currentsite.txt

3---> type the name of the side in the file currentsite.txt


note: this file needs to be created in the folder sites


# install erpnext 
to install the erpnext app you to be in the root of the proyect and run the next command:

bench get-app https://github.com/frappe/erpnext --branch version-13
or 

bench get-app erpnext --branch version-13


# install erpnext app in the site

bench --site [site-name] install-app erpnext


# create an app
bench new-app [app-name]

# install the app created
bench install-app [app-name]




# guia alternativa
https://github.com/sihaysistema/Guia-ERPNext/blob/master/Aprendiendo-a-usar-ERPNext.md#52383---cantidad-de-inventario-proyectado-video-248


