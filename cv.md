# Ihar Charnyshou

## Contacts
* __Location:__ Mogilev, Belarus
* __Phone:__ +375(33)693-74-35
* __Email:__ iiggaarr19912004@gmail.com
* __GitHub:__ [igar1991](https://github.com/igar1991)

## About Me
I work for a small startup. Interested in blockchain technology. Participated in hackathons and grant programs. I like to play chess and mafia.

## Skills
* HTML
* CSS
* JavaScript
* React.js / Redux
* React Native / Expo / Navigation
* Node.js / Express
* Git / GitHub
* Figma / Canva
* Jira / Trello

## Code Example
```
const getTemplateArr = createAsyncThunk('main/getTemplateArr',
    async function (_, { rejectWithValue }) {
        try {
            const response = await fetch(`https://api.imgflip.com/get_memes`)
            if (!response.ok) {
                throw new Error("Server error")
               
            }
            const data = await response.json()
            return data;

        } catch (error) {
            return rejectWithValue(error)
        }

    }
)
```
