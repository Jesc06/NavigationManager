# NavigationManager
<br>

### *Set-up rendermode in page and inject navigation manager*

```razor
@rendermode InteractiveServer
@inject NavigationManager nav

<button type="submit" @onclick="SignUp">Sign in</button>

@code{
   void SignUp(){
        nav.NavigateTo("/signUp");
   }
}
```


