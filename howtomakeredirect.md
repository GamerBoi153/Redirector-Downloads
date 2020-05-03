## How to make redirect

if you have downloaded the extension and want to make a redirect [click here](chrome-extension://ocgpenflpmgnfapjedencafcfakcekcd/help.html#basicusage)

if you have not I reccomend you to but heres how

so you put in the url you want to redirect and then the url you want it to go to, like youtube.com to nsfwyoutube.com

then you make the example url which HAS to be a url that your already using (in this example youtube.com or nsfwyoutube.com)

then done! BUT WAIT

THEN you have to export it and open the json file to make sure it has ONLY the redirect you want and not others, if you have others you have
to get rid of them in the json file. If you think you got rid of the ret make sure it looks almost EXACTLY like this
 (execpt the URLS obviously and disabled and grouped, you know just make sure the lines *37*  through *40*  are the same)
DONT EVEN CHANGE THE NAME OR ANYTHING OZR ELSE IT WILL NOT WORK
\
{
    "createdBy": "Redirector v3.5.3",
    "createdAt": "2020-05-02T23:48:21.692Z",
    "redirects": [
        {
            "description": "",
            "exampleUrl": "https://www.roblox.com",
            "exampleResult": "https://www.roblox.com/login",
            "error": null,
            "includePattern": "https://www.roblox.com",
            "excludePattern": "",
            "patternDesc": "https://www.roblox.com → https://www.roblox.com/login",
            "redirectUrl": "https://www.roblox.com/login",
            "patternType": "W",
            "processMatches": "noProcessing",
            "disabled": false,
            "grouped": false,
            "appliesTo": [
                "main_frame"
            ]
        }
    ]
}
\
