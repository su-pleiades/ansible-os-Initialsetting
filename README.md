# 準備
```sh
python3 -m venv venv 
source venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

# 手順
```sh
ansible-playbook local-os-initialsetting.yml -i hosts -v
```

# 目的
- linuxOSの基本的な初期設定を行う
