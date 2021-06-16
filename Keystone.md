# Openstack Tenent 및 Identity 관리

</br>
<h2>목차</h2>

- Keystone은 무엇인가?
- Region / Domain / Project의 개념
</br>

---

</br>
<h2> Keystone은 무엇인가?</h2>

#

Keystone은 Openstack의 인증을 담당하고 있습니다.

#

어떤 서비스를 설치하더라도 가장 먼저 설치가 되는 가장 중요한 서비스이며, Keystone이 없으면 그 어떤 서비스도 이용할 수 없습니다.

#

따라서, 이렇게 생각을 해볼 수 있습니다.

#

Openstack이 집이라면 Keystone은 현관문 키와 같은 기능을 하는 것이 아닐까?  
Openstack이라는 집은 물리서버로 구성되어 있고, **집 안에는 Compute, Image, Network, Storage와 같은 자원들이 있다고 가정해봅시다.**

#

이러한 자원들이 우리가 평소에 사용하는 가전제품이라고 한다면  
Openstack이라는 집에 들어가야만 사용할 수 있습니다.

#

즉, 내돈내산 가전제품들을 집 주인과 손님만 사용할 수 있습니다.  
이렇듯 Openstack이 제공하는 서비스들도 동일하게 아무나 사용할 수 없습니다.

#


<!--stackedit_data:
eyJoaXN0b3J5IjpbNzI2NzI2MDk2LDY0OTcwMzA2LDI4NDUzMz
c1NSwzNDIzODMyMTAsMTIxMzc1MTQ0NCwxNTAxNzkwODMwXX0=

-->