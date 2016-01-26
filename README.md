#### orintwebperfopti

- W3C Navi process
```
onbeforeunload->navigationstart->redirectstart->unloadstart->unloadend->redirectend
fecthstart(Cache check)->domainlookupstart->domainlookupend(DNS)
connnectstart->(secureconnectstart)->connectend(TCP)
requeststart->requestend->responsestart->responseend
domloading->dominteractive->domcontentloaded->domcomplete
loadeventstart->loadeventend
```

- DOM Const
HTML to DOM tree->Render tree->Layout Render Tree->Paint Render Tree
