# Liferay Faces [](id=liferay-faces-jsf-portlets)

![ ](../../images/04-liferay-faces-logo.png)

Do you want to develop MVC-based portlets using the Java EE standard? Do you
want to use a portlet development framework with a UI component model that
makes it easy to develop sophisticated, rich UIs? Or have you been writing 
web apps using JSF that you'd like to use in Liferay Portal? If you answered yes
to any of these questions, you're in luck! *Liferay Faces* provides all of these
capabilities and more. 

Liferay Faces is an umbrella project that provides support for the
JavaServer&#8482; Faces (JSF) standard within Liferay Portal. It encompasses the
following projects:

- **Liferay Faces Bridge** enables you to deploy JSF web apps as portlets
without writing portlet-specific Java code. It also contains innovative features
that make it possible to leverage the power of JSF 2.x inside a portlet
application. Liferay Faces Bridge implements the JSR 329 Portlet Bridge
Standard. 
- **Liferay Faces Alloy** enables you to use AlloyUI components in a way that
is consistent with JSF development. 
- **Liferay Faces Portal** enables you to leverage Liferay-specific utilities
and UI components in JSF portlets. 

If you're new to JSF, you probably want to know its strengths, its weaknesses,
and how it stacks up to developing portlets with CSS/JavaScript. We'll give you
information on JSF and Liferay Faces to help you decide what framework is best
for your needs. 

Here are some good reasons to use JSF and Liferay Faces:

- JSF is the Java EE standard for developing web applications that utilize the
Model/View/Controller (MVC) design pattern. As a standard, the specification is
actively maintained by the Java Community Process (JCP), and the Oracle
reference implementation (Mojarra) has frequent releases. Software Architects
often choose standards like JSF because they are supported by Java EE
application server vendors and have a guaranteed service-life according to
Service Level Agreements (SLAs).
- JSF was first introduced in 2003 and is therefore a mature technology for
developing web applications that are (arguably) simpler and easier to maintain.
- JSF Portlet Bridges (like Liferay Faces Bridge) are also standardized by the
JCP and make it possible to deploy JSF web applications as portlets without
writing portlet-specific Java code.
- Support for JSF (via Liferay Faces) is included with Liferay EE support.
- JSF is a unique framework in that it provides a UI component model that makes
it easy to develop sophisticated, rich user interfaces.
- JSF has built-in Ajax functionality that provides automatic updates to the
browser by replacing elements in the DOM.
- JSF is designed with many extension points that make a variety of integrations
possible.
- There are several JSF component suites available including Liferay Faces
Alloy, ICEfaces, Primefaces, and RichFaces. Each of these component suites
fortify JSF with a variety of UI components and complimentary technologies such
as Ajax Push.
- JSF is a good choice for server-side developers that need to build web user
interfaces. This enables server-side developers to focus on their core
competencies rather than being experts in HTML/CSS/JavaScript.
- JSF provides the Facelets templating engine which makes it possible to create
reusable UI components that are encapsulated as markup.
- JSF provides good integration with HTML5 markup
- JSF provides the Faces Flows feature which makes it easy for developers to
create wizard-like applications that flow from view-to-view. 
- JSF has good integration with dependency injection frameworks such as CDI and
Spring that make it easy for developers to create beans that are placed within
a scope managed by a container: `@RequestScoped`, `@ViewScoped`,
`@SessionScoped`, `@FlowScoped`
- Since JSF is a stateful technology, the framework encapsulates the
complexities of managing application state so that the developer doesn't have to
write state management code. It is also possible to use JSF in a stateless
manner, but some of the features of application state management become
effectively disabled.

There are some reasons not to use JSF. For example, if you are a
front-end developer who makes heavy use of HTML/CSS/JavaScript, you might find
that JSF UI components render HTML in a manner that gives you less control over
the overall HTML document. So, sticking with JavaScript and leveraging
AlloyUI may be better for you. Or, perhaps standards aren't a major
consideration for you or you may simply prefer developing portlets using your
current framework. 

Whether you develop your next portlet application with JSF and Liferay Faces or
with HTML/CSS/JavaScript is entirely up to you. But you probably want to learn
more about Liferay Faces and try it out for yourself. In the Liferay Faces
tutorials, you'll learn how the Liferay Faces Bridge works, examine using
Liferay UI Components and Utilities in JSF applications, leverage AlloyUI
components using Liferay Faces Alloy, migrate an existing project to Liferay
Faces, and build Liferay Faces from source.

