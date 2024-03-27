script_path=${0:a:h}

printf '\033[33mz4h\033[0m: downloading \033[1mminiconda script\033[0m\n'
wget -q https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh -O "${script_path}/miniconda.sh"

printf '\033[33mz4h\033[0m: installing \033[1mminiconda\033[0m\n'
bash "${script_path}/miniconda.sh" -b -p "${script_path}/miniconda" > /dev/null
rm "${script_path}/miniconda.sh"
