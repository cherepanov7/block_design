# block_design

##Link

https://active-vision.ru/icon/gradient/

https://htmlbook.ru/css/background-attachment

https://wireframe.cc/M8dXw7


##рецепт по блочной верстке

- Когда в родительском блоке есть несколько float эллементов,то он теряет свои параметры высоты, они = 0;


Решение:

```
#name_of_parent_element: :after {
	content:"" ;
	clear:both;
	display:block;
}
```