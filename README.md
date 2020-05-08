# oracle in footloose container machine

this is work in progress and i don't know if it's working at all ;)

needs docker, ansible 2.? <= 2.8, footloose

i use ansible-oracle as submodules

    docker create network oracle-net  # needed to make dns work

    footloose create

    ansible-playbook ora.yml
