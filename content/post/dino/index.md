---
title: Dino Adventure
date: 2024-09-26
image:
  filename: 1.jpg
  focal_point: 'left'
  params:
    width: 100%
---


# 게임 소개
<img src="https://velog.velcdn.com/images/idok/post/7b794c0f-9727-4e4c-9372-a93e349cf428/image.png" width="40%">

<img src="https://velog.velcdn.com/images/idok/post/5bba1ad5-c914-4f20-a370-264e8062b639/image.png" width="40%">

<img src="https://velog.velcdn.com/images/idok/post/fd91ebd7-34b4-474e-9db6-c2e0ce382ff8/image.png" width="40%">



아기 공룡들과 같이 동굴 모험을 하는 2D 플랫포머 장르입니다.

---
# 주요 코드
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

