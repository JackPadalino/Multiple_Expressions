# [Multiple Expressions](https://multiple-expressions.onrender.com/)

Mixcloud/SoundCloud like application for live streaming and showcasing DJ sets.

## Project description

This project was created out of the desire to move away from subscription-based live streaming and music repository services like SoundCloud, Mixcloud, Instagram, and TikTok.
DJ's often want to post and live stream their sets, but have to worry about platforms policing music copyrights, ending streams early, or taking their sets down. Sites like Mixcloud offer DJ's the ability to stream without the worry of copyright, but for a monthly fee. This project was developed out of a personal desire to post and play whatever we like, without having to adhere to
a platform's policies.

## Links

- [Deployed site](https://multiple-expressions.onrender.com/)
- [Backend repository](https://github.com/JackPadalino/Multiple_Expressions_backend)
- [Frontend repository](https://github.com/JackPadalino/Multiple_Expressions_frontend)

## Created With

Frontend -

- React
- React Router
- Redux
- Wavesurfer.js
- Axios
- Framer Motion
- MUI Components

Backend -

- Django
- Django Rest Framework
- Django Storages
- AWS S3 Buckets
- AWS Interactive Streaming Services

## Deployments

- Frontend and backend deployed separately using [Render](https://render.com/)
- Media files like photos and mp3 files are stored and served using [AWS S3 Buckets](https://aws.amazon.com/pm/serv-s3/?gclid=CjwKCAiArLyuBhA7EiwA-qo80DuR-1Ho0HlpGEAZpJ7nbzlrV9BHsflgbBoIbvyVfJ6UekQgGMNvkhoCeeYQAvD_BwE&trk=fecf68c9-3874-4ae2-a7ed-72b6d19c8034&sc_channel=ps&ef_id=CjwKCAiArLyuBhA7EiwA-qo80DuR-1Ho0HlpGEAZpJ7nbzlrV9BHsflgbBoIbvyVfJ6UekQgGMNvkhoCeeYQAvD_BwE:G:s&s_kwcid=AL!4422!3!536452728638!e!!g!!amazon%20s3!11204620052!112938567994)
- Live streaming is handled using [AWS Interactive Streaming Sercices](https://aws.amazon.com/pm/ivs/?gclid=CjwKCAiArLyuBhA7EiwA-qo80DEIg6PNxOBGC80HJIM2W8_tLNZr0A65R3LQ5EwJW3hb5Gn4k79vARoC32AQAvD_BwE&trk=d097123b-f91d-4460-815b-85c3ddbefdc4&sc_channel=ps&ef_id=CjwKCAiArLyuBhA7EiwA-qo80DEIg6PNxOBGC80HJIM2W8_tLNZr0A65R3LQ5EwJW3hb5Gn4k79vARoC32AQAvD_BwE:G:s&s_kwcid=AL!4422!3!629393326042!!!g!!!16080176303!133788124998)

## Ongoing work

Frontend -

- Use all MUI components for divs and containers
- Update fonts
- Update styling of chat feature
- Continue to add pictures, videos, tracks from various artists
- Add landing page with most recently updated track
- 'Report an issue' form
- Pagination for Auditory component
- Render actual waveforms for tracks - Rendering randomly generated waveforms for now
- 'Meet the Crew' page
- Resolve scrolling issue with live stream chat

Backend -

- Multipart uploading to handle larger media files like videos
- Adding user accounts and authentication

## **DISCLAIMER**

This project is strictly a portfolio piece. I do not claim the rights to any music hosted on the platform.
If there any questions/concerns about any copyrighted music hosted on the platform please contact me.
