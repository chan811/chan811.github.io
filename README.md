# Welcome to my homepage!

![Image](https://chan811.github.io/images/imageChanly.png) ***<- Me!!!***

## Social Media
[Linkedln](https://www.linkedin.com/in/chanly-ly-89869519b/)

[Instagram](https://www.instagram.com/chan__811/)

### About Me
>I am a transfer student @UCSD majoring in computer engineering. 
>Something nerdy about me is that when I am not practicing leetcode I would look up random algorithms and try to understand them.
>One really cool algorithm that I have seen is the inverse square algorithm from the video game Quake III which used to quickly approximate 
>the inverse square. I hope to one day be able to come up with a beautiful algorithm like the one from Quake III.

**The inverse square algorithm from Quake III**
```
float Q_rsqrt( float number )
{
	long i;
	float x2, y;
	const float threehalfs = 1.5F;

	x2 = number * 0.5F;
	y  = number;
	i  = * ( long * ) &y;                       // evil floating point bit level hacking
	i  = 0x5f3759df - ( i >> 1 );               // what the fuck? 
	y  = * ( float * ) &i;
	y  = y * ( threehalfs - ( x2 * y * y ) );   // 1st iteration
//	y  = y * ( threehalfs - ( x2 * y * y ) );   // 2nd iteration, this can be removed

	return y;
}
```

### Hobbies
1. Skating
2. Tennis
3. Collecting figures/pins/stickers and more
4. Gaming

### Languages
- C
- C#
- C++
- Java
- Shell
- ARM Assembly


### To Do List
- [ ] Add voice commands to discord bot
  - [ ] Test hotword detection
  - [ ] Utilize Google API to translate voice to text
- [ ] Learn python
- [ ] Work on arduino project

[**Project List**](doc/project.md)
