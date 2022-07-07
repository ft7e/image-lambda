# image-lambda

## How lambda works

whenever we upload an image, the function will be excuted and the metadata of the image will be stored in the image.json

## imageJSON Link

[ImageJSON](https://wista03.s3.us-east-1.amazonaws.com/imagesJSON.txt?response-content-disposition=inline&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaDGV1LWNlbnRyYWwtMSJHMEUCIQDFe2NTeupbaIEAPRAdbNOWaTVNs2AGlz0ccEHLTd0%2BZgIga6QIpsfAtkerC5npcNlIjVZZ%2BTc%2Fpg1rZ4S%2BuMsg3JcqiAMI0f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw5OTQ5NzA3MzE1MjEiDOsJRHNlj90ekS7hxircAt8u3uQOkhVUKNVG7FJVA%2FVTSWPkjViS1oj8aj37KJnkUn0jl5hoObZFVawtLhl4rSYx9vcnrmkyyzr%2FaFkSvG%2FsZL86KAZ5Vfq9aEcNdjyYLKuPKh0trLQnh99zBqp9VYJvJ120Vc8O6kw2U2%2Fb1TxUBpL%2BovtOqMpVpG2Gyjvb0uBCa%2FaoJEH%2FBAGBfiXi5f5IBUoeIkdgooWhbKo87zGXbqMBcPNj%2F2lG1pLUIpCt3zDetb3vhL0ALS3uPRFe7qnrHf65JkfTLcnwbjaZLURG%2BdUd7Xir5QXaL2DvAlXs%2BkwL8AiaKkcKdPZ9Yt9QD1dF5Gwl4YKonbaPBwAdCGG9DKJf2YbUdNTktg9Y4GzTcrvG9fhyB4I%2Bkl8jTNQxWoSQNBHAU4qsZ4sJjbDXWKrg0C6p1gdD7arzpgejayCyoz%2FPD0L2lTIfaCDmCywezblUn2VlDFNeWBlr%2FjCWlJqWBjqzAuW%2FZQT2b3XTJQ9dy4qv4RdZ9nqoWTWrWwkCa0MiaGe69mlg0UgjLI3hgLg%2Bxu5kwNvJtlLEPMEt9dyAlynLWF%2Bf0oUKlajgNrMd0cwHOqii7sFm6UZEspR2YBgC%2BQvt%2BlEM83xEcvKUepy6NTnypLhw4h2b68D5MdTKq1x1nP8uIjneUkeV8qBnOfoY6u4RU3iwmONy2rBnP91eGB%2F9fYDWZkcGqUhIkqsFq0rYX7MTu7WWE7NNCdzDSnNa%2FG%2BhV2D3dxNHo6S4WJX%2BZc0pXXcM5ov8%2FtsrHEerxg30bLCvWctPy3lbNsQZp%2Bm66jVqPK%2FTrV61AHe9h4WL7Md%2BGUr76XYV9JyudU03Z3cgxxy1liOlwuBLF5fFpYue0jGlwBdfJxVsHb4MgbdEliqpXqqgFco%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20220707T110103Z&X-Amz-SignedHeaders=host&X-Amz-Expires=299&X-Amz-Credential=ASIA6PKHAQQATUDTGIOH%2F20220707%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=b8ac5c537d5656a3c56d2ae0eb3f7f44e14ca9cdc1abf7a2879e33e949124cac)

## Uploaded Image link

[Uploaded Image](https://wista03.s3.us-east-1.amazonaws.com/LK4.jpg?response-content-disposition=inline&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaDGV1LWNlbnRyYWwtMSJHMEUCIQDFe2NTeupbaIEAPRAdbNOWaTVNs2AGlz0ccEHLTd0%2BZgIga6QIpsfAtkerC5npcNlIjVZZ%2BTc%2Fpg1rZ4S%2BuMsg3JcqiAMI0f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw5OTQ5NzA3MzE1MjEiDOsJRHNlj90ekS7hxircAt8u3uQOkhVUKNVG7FJVA%2FVTSWPkjViS1oj8aj37KJnkUn0jl5hoObZFVawtLhl4rSYx9vcnrmkyyzr%2FaFkSvG%2FsZL86KAZ5Vfq9aEcNdjyYLKuPKh0trLQnh99zBqp9VYJvJ120Vc8O6kw2U2%2Fb1TxUBpL%2BovtOqMpVpG2Gyjvb0uBCa%2FaoJEH%2FBAGBfiXi5f5IBUoeIkdgooWhbKo87zGXbqMBcPNj%2F2lG1pLUIpCt3zDetb3vhL0ALS3uPRFe7qnrHf65JkfTLcnwbjaZLURG%2BdUd7Xir5QXaL2DvAlXs%2BkwL8AiaKkcKdPZ9Yt9QD1dF5Gwl4YKonbaPBwAdCGG9DKJf2YbUdNTktg9Y4GzTcrvG9fhyB4I%2Bkl8jTNQxWoSQNBHAU4qsZ4sJjbDXWKrg0C6p1gdD7arzpgejayCyoz%2FPD0L2lTIfaCDmCywezblUn2VlDFNeWBlr%2FjCWlJqWBjqzAuW%2FZQT2b3XTJQ9dy4qv4RdZ9nqoWTWrWwkCa0MiaGe69mlg0UgjLI3hgLg%2Bxu5kwNvJtlLEPMEt9dyAlynLWF%2Bf0oUKlajgNrMd0cwHOqii7sFm6UZEspR2YBgC%2BQvt%2BlEM83xEcvKUepy6NTnypLhw4h2b68D5MdTKq1x1nP8uIjneUkeV8qBnOfoY6u4RU3iwmONy2rBnP91eGB%2F9fYDWZkcGqUhIkqsFq0rYX7MTu7WWE7NNCdzDSnNa%2FG%2BhV2D3dxNHo6S4WJX%2BZc0pXXcM5ov8%2FtsrHEerxg30bLCvWctPy3lbNsQZp%2Bm66jVqPK%2FTrV61AHe9h4WL7Md%2BGUr76XYV9JyudU03Z3cgxxy1liOlwuBLF5fFpYue0jGlwBdfJxVsHb4MgbdEliqpXqqgFco%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20220707T105904Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIA6PKHAQQATUDTGIOH%2F20220707%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=9103407708aa0d4e0ca12f1cc3e586e83e81323afc53e21b5535173d67d99144)
