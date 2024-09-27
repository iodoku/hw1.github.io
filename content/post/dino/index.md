---
title: Dino Adventure
date: 2024-09-26
image:
  filename: 1.jpg
  focal_point: 'left'
  params:
    width: 100%
---


아기 공룡들과 같이 동굴 모험을 하는 2D 플랫포머 장르입니다.

- 담당 파트 : 1인개발

- 게임 사양 : 

- 제작 기간 : 2024.05.20~2024.07.08

---
```C#
void OnFire(InputValue value)
    {
        Dino currentdino= FindObjectOfType<Dino>();
        if(currentdino == null) { return; }
        if(currentdino.hasbullet&&curbulletnum>0)
        {
            GameObject tmpbullet=Instantiate(currentdino.bullet,currentdino.gunpos.position, transform.rotation);
            curbulletnum--;
            if (transform.localScale.x<0)
            {
                tmpbullet.transform.localScale = new Vector2(-1f,1f);
            }   
        }
    }
```
Dino 클래스의 hasbullet을 통해 아기 공룡이 공격할 수 있는지 없는지 파악하고 공격 가능하다면
플레이어가 바라보는 방향에 맞춰 localscale을 조정해 탄환을 발사합니다.

