Mobile-Secure-Containers-Presentation
=====================================
<b>Presented By</b>
Ron Gutierrez
<br />

<b>Abstract</b>

In today's world, everyone wants access to information from his or her personal mobile device.  As a business, this includes your customers and/or employees.  What if the information they want access to is highly sensitive?  While it's tempting to resist these pressures for security reasons, providing mobile access can be a significant competitive advantage and most importantly keep your customers and employees happy and productive. The reality is that in order to survive in a connected world, we must provide a way to meet these demands without sacrificing security.  

Organizations have begun moving from "managed devices" to a Bring Your Own Device (BYOD) model where company resources can be accessed and stored on unmanaged devices. As you can imagine, there are some inherent risks with this approach due to the organizations inability to enforce policies on personal devices. There is currently a huge market for solutions that allowing enterprises protect their data on unmanaged devices. Enter "Secure Containers” and “Application Wrapping". The basic premise of these solutions is that it allows organizations enforce policies at the application layer rather than the device layer. For example, authentication, remote wipes, lockouts and data encryption can now be enforced on a per application basis. Application Wrapping is a technique, which allows the ability inject their own code into existing iOS applications. Once injected, existing iOS method implementations can be overwritten to enforce these policies. In a nutshell, you can have an existing application and have it wrapped so that it enforces various defined policies and secure it without developers having to manually implement it.  

We have performed security assessments of various commercial BYOD solutions and custom secure containers. Additionally, we have also provided guidance in the development and design of such solutions. We plan to share our experiences through various case studies showcasing the various security issues encountered and testing techniques used throughout these assessments. We expect to cover and provide the audience with newfound knowledge in the following topics:  

What is Application Wrapping and How It Is Implemented
<ui>
<li>Dynamic Library Injection</li>
<li>iOS Method Swizzling</li>
</ul>

Walkthrough of Common Designs for Secure Containers
<ul>
<li>Weak Crypto Key Storage and Generation</li>
<li>Common Crypto Implementation Flaws</li>    
<li> Online and Offline Authentication Designs</li>
</ul>

Leveraging iOS Runtime Analysis for Reversing Implementations
<ul>
<li>Common iOS Reversing Techniques</li>
<li>Writing Mobile Substrate Hooks</li>
</ul>

Completeness of the Implementation
<ul>
<li>Preventing Common Mobile Security Plaintext Storage Issues</li>
<li>Inadvertent Caching of Sens</li>
<li>Jailbreak Detection</li>
</li>Weaknesses in Policy Enforcement and Remote Wipes</li>
</ul>

Attendees will leave with an understanding of the advantages and disadvantages of using "secure container" solutions. The presentation will be delivered from the point of view of a security tester with experience in assessing various implementations. Organizations can leverage this knowledge in order to perform informed decisions when choosing or developing solutions. Security testers will leave with baseline checks and testing techniques for assessing secure container implementations. 
