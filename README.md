# laravel_docker © [DevHub](https://t.me/devhub_az)
- [Laravel](https://laravel.com)
- [Docker](https://www.docker.com)

## İstifadəsi

Başlamaq üçün sisteminizdə [Docker quraşdırılmış](https://docs.docker.com/docker-for-mac/install/) olduğundan əmin olun və sonra bu repo klonlaşdırın. Bütün Laravel layihənizi `src` qovluğuna əlavə edin, sonra terminal açın və bu klonlanmış repozituranın kökünən işə salın `docker-compose build && docker-compose up -d`. 

[http://localhost:8080](http://localhost:8080) brauzerinizdə açın və Laravel tətbiqinizin nəzərdə tutulduğu kimi işlədiyini görməlisiniz. 

Yaradılmış konteynerlər və portalları:

- **nginx** - `:8080`
- **mysql** - `:3306`
- **php** - `:9000`