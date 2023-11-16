# How to talk to the Beast

To enter your api key: Go to the file src/pages/Ethics.js and replace the key with your own

```
import React, {useState} from "react";
import OpenAI from "openai";
import ResponseComponent from "../components/Response";
import "../styles/Ethics.css";
import video2 from "../assets/EthicsBackground.mp4"

const openai = new OpenAI({
    apiKey: "",
    dangerouslyAllowBrowser: true
});
```

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.
