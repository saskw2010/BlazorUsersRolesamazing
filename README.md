# Blazor Users Roles Amazing
##Mostafa Elnagar

#Good solution in razor pages authorizeview
Razor Pages is a framework for building web applications with ASP.NET Core. It is based on the Model-View-Controller (MVC) pattern, and provides a convenient way to build web pages that display data, accept input, and perform logic. Razor pages authorizeview is a Razor component that can be used to display content based on the user's authorization status.

One way to use the AuthorizeView component in Razor pages is to wrap it around the content that you want to protect. For example:
 ```csharp
 @using Microsoft.AspNetCore.Authorization
  
  @page

  @attribute [Authorize]

  <AuthorizeView>
     <Authorized>
          <h1>Welcome!</h1>
          <p>You are logged in and have access to this content.</p>
     </Authorized>
     <NotAuthorized>
         <h1>Sorry</h1>
          <p>You are not logged in and do not have access to this content.</p>
     </NotAuthorized>
  </AuthorizeView>
```  
  
This will display the "Welcome!" message to users who are logged in, and the "Sorry" message to users who are not logged in. You can also use the Policy attribute to specify which users have access to the content, based on their claims or roles.

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

This expression uses `\$` to display a dollar sign: $\sqrt{\$4}$

###
<h1>
      Mostaf Elnagar (LINKEDIN) Profile On 2023-01-01[Click_Here_pdf](https://github.com/saskw2010/BlazorUsersRolesamazing/files/10368991/MostafelnagarLINKEDIN2023-01-01.pdf)
 [MostafelnagarLINKEDIN2023-01-01.pdf](https://github.com/saskw2010/BlazorUsersRolesamazing/files/10369019/MostafelnagarLINKEDIN2023-01-01.pdf)

</h1>

