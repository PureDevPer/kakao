# Animation

How to make the `animation`:

```css
.box {
	animation: 1.5s ANIMATION_NAME ease-in-out;
}

@keyframe ANIMATION_NAME {
	from {
		transform: none;
	}
	to {
		transform: rotate(1turn) scale(0.5, 0.5);
	}
}

@keyframe ANIMATION_NAME_1 {
	0% {
		transform: none;
	}
	50% {
		transform: rotate(1turn) scale(0.5, 0.5);
	}
	100% {
		transform: none;
	}
}
```
