# GoVM - Virtualization Manager in Go

Welcome to the main project repository for GoVM, a user-friendly Virtualization Manager built with Go.

GoVM aims to provide an easy and straightforward interface for managing servers, making it accessible even to those without advanced technical skills. We believe in the power of simplicity, which is why our interface follows a "keep it simple" approach, allowing users to manage their environments with ease and confidence.

For more details and to follow the progress of this project, please visit [the GoVM Project Tracker](https://github.com/hyperifyio/project-govm/issues/1).

## Availability

The complete source code for GoVM is available under [the FSL-1.1-MIT license](./LICENSE.md). You can explore the codebases here:

* [govm Server Project](https://github.com/hyperifyio/govm)
* [govm Frontend Project](https://github.com/hyperifyio/frontend-govm)
* [govm Frontend Source Code](https://github.com/hyperifyio/io.hyperify.govm)

The FSL-1.1-MIT license is a flexible software license that combines the permissiveness of the MIT license with additional terms specified under the FSL-1.1. It allows users to freely use, modify, and distribute the software, provided they adhere to the specific conditions outlined in the license. The license is designed to encourage open source collaboration while offering clarity on commercial use and distribution. For full details, please refer to [the LICENSE.md file](./LICENSE.md).

## Summary of Commercial Uses

This section provides a general overview of what types of commercial use are typically accepted or not accepted under the Functional Source License (FSL-1.1-MIT). Please refer to [the full license text](./LICENSE.md) for the legally binding terms and conditions.

***Accepted Commercial Uses:***

1. **Internal Business Use:** You are welcome to use the Software within your organization for internal operations, such as improving your business processes or supporting your company's 
   internal projects.

2. **Educational and Research Purposes:** Although these uses are generally non-commercial, they are permitted. Any incidental commercial benefits that arise from educational or research 
   activities within a commercial entity are also acceptable.

3. **Professional Services:** You may use the Software to provide professional services, such as consulting, training, or implementation, as long as these services are provided to a 
   licensee using the Software in accordance with the license terms.

***Not Accepted Commercial Uses (Competing Uses):***

1. **Creating Substitutes:** You may not use the Software to create or distribute a product or service that directly competes with the Software. This includes reselling, rebranding, or 
   repackaging the Software as a commercial offering.

2. **Competing with Existing Products or Services:** Using the Software in a way that competes with any other product or service offered by the Licensor, particularly those existing at the 
   time the Software is made available, is not permitted.

3. **Offering Similar Functionality:** You cannot use the Software to develop or distribute a commercial product or service that replicates or closely imitates the functionality of the 
   Software.

***Flexible Licensing Options***

We understand that different projects may have unique needs. If you have specific requirements or are interested in exploring alternative licensing arrangements, please reach out to our sales team at [sales@hg.fi](mailto:sales@hg.fi) to discuss flexible dual-licensing options.

## Screenshot

![Screenshot 2024-08-16 at 11 20 01](https://github.com/user-attachments/assets/f794818b-5527-4ca9-87ac-799177f3bca1)

## Key Features

* Ease of Use: Designed with simplicity in mind, GoVM ensures that managing servers is straightforward, requiring minimal technical experience.
* Backend Server: Developed in *Go*, providing robust and scalable REST API to manage servers.
* Web Frontend: Built with *ReactJS*, offering an intuitive and responsive user interface that aligns with our "keep it simple" philosophy.
* Virtual server enrollment: Cloud Init -based virtual server creation (support still experimental)
* Virtual server management: Stop, Start, Reboot, and VNC console available
* Translation: Finnish and English (and easy to add more!)

## System Requirements

GoVM is designed to run on the following operating systems:

* Linux (our main focus)
* macOS

Future options (not tested yet, nor officially supported yet):

* Windows
* FreeBSD


