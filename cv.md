# Sergey Prokopenya

## Contact Information

---

**Email:** sera.prokop@gmail.com  
**Discord:** @sera-prokop  
**Github:**  [https://github.com/sera-prokop](https://github.com/sera-prokop)  
**Telegram** [https://t.me/sera_prokop](https://t.me/sera_prokop)

## About me

---

My goal is to improve theoretical knowledge and get practical experience in building web applications.

## Skills

---

* HTML, CSS
* Git, Github, Subversion
* JavaScript
* Sass, Less
* Pug, Handlebars
* PostCSS
* React, Vue (basic)
* NodeJS, Express, MongoDB (basic)

## Code example

---

```
import Card from '../../shared/components/UIElements/Card'
import './PlaceList.css'
import PlaceItem from './PlaceItem'
import Button from '../../shared/components/FormElements/Button'

const PlaceList = (props) => {
    if (props.items.length === 0) {
        return (
            <div className="place-list center">
                <Card>
                    <h2>No places found.</h2>
                    <Button to="/places/new">Share place</Button>
                </Card>
            </div>
        )
    }

    return (
        <ul className="place-list">
            {props.items.map((place) => (
                <PlaceItem
                    key={place.id}
                    id={place.id}
                    image={place.imageUrl}
                    title={place.title}
                    description={place.description}
                    address={place.address}
                    creatorId={place.creator}
                    coordinates={place.location}
                />
            ))}
        </ul>
    )
}

export default PlaceList
```

## Work experience

---

For several years he worked in several institutions as a layout designer

## Education

---

* [https://loftschool.com/](https://loftschool.com/)
* [https://htmlacademy.ru/](https://htmlacademy.ru/)
* [https://learn.javascript.ru](https://learn.javascript.ru)

## Languages

---

* **English:** Pre-intermediate
* **Russian:** Native


