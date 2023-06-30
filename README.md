# README

<strong>環境構築方法</strong>
- ターミナルでファイルを保存するディレクトリへ移動
- git clone https://github.com/mutsuki15/rails-docker.git
- Dockerを起動させる
- docker-compose up
- ターミナルの新規タブを開き、ファイルが保存されているディレクトリへ移動
- docker-compose run web rake db:create
- docker-compose exec web bash
- rails db:migrate
- rails webpacker:install
- ブラウザでlocalhost:3000を開く