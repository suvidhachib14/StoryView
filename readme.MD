# StoryView

## A library to create awesome stories in your app similar to new Whatsapp status update.

## Usage

### Creating a Story(In Activity)

```
    Story story = Story.getInstance(this);
```

### Creating a Status(In Activity)

```
    Status status = Status.newInstance(BitmapFactory.decodeResource(getResources(),R.drawable.kol),"Kings Of Leon",new Date());
```

### Adding status to a Story

```
    story.addStatus(status);
```

### Adding profile to the story

```
    story.setProfilePart(BitmapFactory.decodeResource(getResources(),R.drawable.profile_img),"Anwesh");
```

### Showing the story

```
    story.show();
```

### Demo

<img src="https://github.com/Anwesh43/StoryView/blob/master/screenshots/storyview.gif" width="400" height="700">
