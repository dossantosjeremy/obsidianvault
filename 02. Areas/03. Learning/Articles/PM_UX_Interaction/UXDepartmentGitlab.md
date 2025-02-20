![gitlab-cover.png](attachment:e8271391-b545-42a0-8f68-b8e26a686651:gitlab-cover.png)

The GitLab UX department comprises four areas to support designing the GitLab product: UX Research, Product Design, Technical Writing, and Foundations

## Hello

We’re the GitLab User Experience (UX) department. We comprise four areas to support designing and building the GitLab product.

- [UX Research](https://handbook.gitlab.com/handbook/product/ux/ux-research/)
- [Technical Writing](https://handbook.gitlab.com/handbook/product/ux/technical-writing/)
- [Product Design](https://handbook.gitlab.com/handbook/product/ux/product-design/)
- Foundations - [Pajamas](https://design.gitlab.com/)

Our goal is to make our product easy to use, supportive of contributions from the wider GitLab community, and built for a diverse global community. We want GitLab to be the easiest and most delightful product in its class.

## How we work

- **We support all users from beginners to experts.** We believe that GitLab software should be unintimidating and accessible for a beginner, without oversimplifying important features for advanced users. We stay with users every step of the way to help them learn fast as a beginner and then become an expert over time.
- **We’re building one product, together.** We’re highly focused on ensuring that no matter how big our product gets, the entire experience stays cohesive, consistent, and interconnected.
- **We’re humble facilitators of user experience design.** Everyone is a designer; [everyone can contribute](https://docs.gitlab.com/development/ux/). We are not egotistical, moody experts who alone hold the keys to user delight. We encourage Product Managers, Engineers, and the wider GitLab community to contribute to creating an exceptional user experience.
- **We look for small changes and big impacts.** Sometimes the simplest, most boring solution is what is needed to make users successful. We want our UI to stay out of the user’s way. We work iteratively to make modest but valuable changes that make users more productive, faster, and better at accomplishing their tasks.
- **We’re informed by empathy.** We’re human, and we design for humans, so we strive for understanding, self-awareness, and connection. We are quirky, and we introduce our quirks into designs when appropriate.
- **When we find problems that are simple to fix, we are empowered to make those changes ourselves.** If a change will take you less than 15 minutes to make (for example, a minor change to our website or microcopy in the product), then start with an MR instead of an issue. By making the change yourself, you are taking immediate action to improve our product, and you might learn a new skill, too! If it seems simple, but you have questions, remember that there are people who can help you with code changes both in the UX department and across the company.

We work closely with the community, and our stable counterparts Product Managers (PM), Frontend engineers (FE), Backend engineers (BE), Quality engineers, and the Brand team. We follow GitLab’s shared process referred to as the [Product Development Flow](https://handbook.gitlab.com/handbook/product-development-flow/).

- PMs define the “what” and “why” to lead the product direction. These are the benefits we provide to users. It’s informed by gathering customer and user feedback in partnership with UX Research.
- Product Designers define “how” the direction is experienced. It’s how users interact with the product to gain the benefits.
- Engineers define “how” the product is built to meet the product and experience direction from PM and Product Design.

### Workflows

- [UX Researcher](https://handbook.gitlab.com/handbook/product/ux/ux-research/)
- [Technical Writing](https://handbook.gitlab.com/handbook/product/ux/technical-writing/workflow/)
- [Product Designer](https://handbook.gitlab.com/handbook/product/ux/product-designer/)
- [Product Design Manager](https://handbook.gitlab.com/handbook/product/ux/product-design/product-design-manager/)
- [Cross-functional Prioritization](https://handbook.gitlab.com/handbook/product/product-processes/cross-functional-prioritization/)

### Headcount planning

Every Product Designer is aligned with a PM and is responsible for the same customer benefits the PM oversees. Technical Writers each support multiple stage groups. UX Researchers support multiple groups within a section.

In the spirit of having stable counterparts, we plan headcount as follows:

- **One Product Designer for every stage group.**
    - 1:1 ratio of Product Designers to PM (excludes stage groups with no user-facing impact or, in some cases, stage groups with low usage).
    - 1 Product Designer for 1-3 Frontend engineers; 2 Product Designers for 4-5 Frontend engineers.
- **One Technical Writer for up to three stage groups.**
    - 1:3 ratio of Technical Writers to stage groups.
    - Approximately a 1:21 ratio of Technical Writers to Engineers.
- **One UX Researcher for up to 5 stage groups.**
    - 1:5 ratio of UX Researchers to Product Managers.
    - Approximately a 1:35 ratio of UX Researchers to Engineers.
- **Manager support that’s appropriate for the function.**
    - Approximately a 1:5 ratio of Managers to direct reports for UX Research and Product Design.
    - Approximately a 1:7 ratio of Managers to direct reports for Technical Writing.

### UX labels

GitLab uses labels to categorize, prioritize, and track work. The following is a breakdown of the labels most directly related to the UX workflow. An overview of all the label types and uses can be found in the [contributing doc](https://gitlab.com/gitlab-org/gitlab-foss/blob/master/doc/development/contributing/issue_workflow.md).

- 
    
    [**UX** label](https://gitlab.com/groups/gitlab-org/-/issues?scope=all&utf8=%E2%9C%93&state=opened&label_name[]=UX): Indicates that UX work is required on this issue. These issues can be new features, ideas for improvement or anything else where UX should contribute their expertise.
    
- 
    
    [**Inclusion** label](https://gitlab.com/groups/gitlab-org/-/labels?utf8=%e2%9c%93&subscribed=&search=Inclusion): A change to GitLab that promotes inclusion as it relates to our [diversity](https://handbook.gitlab.com/handbook/values/#diversity) value.
    
- 
    
    [**Inclusive design** label](https://gitlab.com/groups/gitlab-org/-/labels?utf8=%e2%9c%93&subscribed=&search=Inclusive+design): Considering, exploring, and evaluating the different ways someone would access, interact with, or contribute to content that results in a more accessible experience.
    
- 
    
    **Accessibility and scoped accessibility labels** are used to identify issues with accessibility impact. The scoped labels should be added after an accessibility audit has validated the impact and used in combination with [priority](https://handbook.gitlab.com/handbook/engineering/infrastructure/engineering-productivity/issue-triage/#priority) and [severity](https://handbook.gitlab.com/handbook/engineering/infrastructure/engineering-productivity/issue-triage/#severity) labels to [triage](https://handbook.gitlab.com/handbook/engineering/infrastructure/engineering-productivity/issue-triage/) an issue.
    
    - [**Accessibility** label](https://gitlab.com/groups/gitlab-org/-/labels?utf8=%e2%9c%93&subscribed=&search=%22Accessibility%22): Issues that contain actionable items that help create an accessible product experience.
    - [**Accessibility-audit** label](https://gitlab.com/groups/gitlab-org/-/labels?utf8=%E2%9C%93&subscribed=&search=%22Accessibility-audit%22): Issues related to auditing exisiting experiences in order to understand possible accessibility-related improvements.
    - [**Accessibility-ops** label](https://gitlab.com/groups/gitlab-org/-/labels?utf8=%E2%9C%93&subscribed=&search=%22Accessibility-ops%22): Issues related to building accessibility into our internal workflows.
    - `accessibility::critical`: Prevents some or all users from performing critical tasks with no possible workaround.
    - `accessibility::high`: Prevents some users from performing critical tasks. A workaround may exist, but not without creating frustration and inefficiency.
    - `accessibility::medium`: Prevents some users from performing non-critical tasks, or where the user experience is seriously degraded for users with certain assistive technologies.
    - `accessibility::low`: The user experience is degraded for users with certain disabilities or using certain assistive technologies, but users can still accomplish tasks.
- 
    
    [**learnability** label](https://gitlab.com/gitlab-org/gitlab/-/issues/?label_name%5B%5D=learnability): Issues that address learnability problems by helping users quickly become familiar with GitLab features.
    
- 
    
    **Scoped workflow labels** from the [Product Development Flow](https://handbook.gitlab.com/handbook/product-development-flow/#validation-phase-1-validation-backlog) should be used to indicate where an issue is in the development lifecycle. Issues can move between workflow labels as many times as necessary, and not all labels will be applicable to every issue. Issues that require UX would use one of these labels as defined in the Product Development Flow:
    
    - `workflow::validation backlog`
    - `workflow::problem validation`
    - `workflow::design`
    - `workflow::solution validation`
- 
    
    **Pajamas component lifecycle labels** are scoped labels used for creating and updating [Pajamas](https://design.gitlab.com/) components. Label usage guidelines can be found in the [Pajamas component lifecycle documentation](https://design.gitlab.com/get-started/lifecycle/).
    
- 
    
    [**UX problem validation** label](https://gitlab.com/groups/gitlab-org/-/issues?scope=all&utf8=%E2%9C%93&state=opened&label_name[]=UX%20problem%20validation): Indicates that the issue requires UX work to validate that the problem is relevant to users. We use this label in addition to the Product Development Flow scoped labels, so that we can track validation efforts over time in our [UX Performance Indicators](https://handbook.gitlab.com/handbook/product/ux/performance-indicators/).
    
- 
    
    [**UX solution validation** label](https://gitlab.com/groups/gitlab-org/-/issues?scope=all&utf8=%E2%9C%93&state=opened&label_name[]=UX%20solution%20validation): Indicates that the issue requires tasks to validate that the proposed solution is technically feasible and meets user needs. We use this label in addition to the Product Development Flow scoped labels, so that we can track validation efforts over time in our [UX Performance Indicators](https://handbook.gitlab.com/handbook/product/ux/performance-indicators/).
    
- 
    
    [**UI polish** label](https://gitlab.com/groups/gitlab-org/-/issues?scope=all&state=opened&utf8=%E2%9C%93&label_name%5B%5D=UI+polish): Indicates the issue covers *only* visual improvement(s) to the existing user interface.
    
- 
    
    [**Deferred UX** label](https://gitlab.com/groups/gitlab-org/-/labels?subscribed=&sort=relevance&search=deferred+ux): Deferred UX results from the intentional decision to deviate from the UX vision or MVC, which sacrifices the user experience. Deferred UX labeled issues are to be included in subsequent releases. Use this label to indicate that the UX released does not meet:
    
    - UX and Pajamas specifications
    - Usability standards
    - Feature viability standards
    
    This label is applied to any follow-up issues that address a UX gap. It does not apply to the issue or merge request that created the Deferred UX. For example, if the agreed MVC design solution is not fully realized due to release pressures or implementation oversight, that’s considered Deferred UX.
    
    If the design is implemented correctly but unforeseen UX issues are identified, it is *not* considered Deferred UX.
    
    If in doubt about when to apply this label, use the following rule: If you can say “This UX problem did not originate from an issue or merge request,” then it’s just UX, not Deferred UX. In case your team makes the decision ship an MVC that contains Deferred UX, it is recommended to create an issue to track it as soon as the change has been released.
    
- 
    
    [**Learn more about Deferred UX as a UX Department Performance Indicator**](https://handbook.gitlab.com/handbook/product/ux/performance-indicators/#deferred-ux).
    
- 
    
    [**UX Paper Cuts** label](https://gitlab.com/groups/gitlab-org/-/merge_requests?scope=all&state=opened&label_name[]=UX%20Paper%20Cuts): Used to prioritize and track work from the UX Paper Cuts team.
    
- 
    
    [**Seeking community contributions**](https://gitlab.com/groups/gitlab-org/-/issues?state=opened&label_name[]=Seeking+community+contributions&assignee_id=0&sort=weight)
    
- 
    
    [**System Usability Scale (SUS)** labels](https://gitlab.com/gitlab-org/gitlab/-/labels?subscribed=&search=sus): Indicates that the issue is related to usability problems surfaced in one of our SUS research efforts. More specifically, issues related to SUS that are prioritized can be labeled with the corresponding Fiscal Year and Quarter. For example: `SUS::FY22 Q2 - Incomplete`. [**Learn more about SUS score as a UX Department Performance Indicator**](https://handbook.gitlab.com/handbook/product/ux/performance-indicators/#perception-of-system-usability)
    
- 
    
    [**Regression** label](https://gitlab.com/groups/gitlab-org/-/issues?scope=all&state=opened&utf8=%E2%9C%93&label_name%5B%5D=regression): Indicates a bug introduced in the latest release that broke correct behavior (see the [contribution guidelines](https://gitlab.com/gitlab-org/gitlab-ce/blob/master/CONTRIBUTING.md#regression-issues) for more info).
    
- 
    
    [**UX scorecard** label](https://gitlab.com/groups/gitlab-org/-/issues?scope=all&utf8=%E2%9C%93&state=opened&label_name[]=UX%20scorecard): Indicates the primary issue or epic for the [UX Scorecard](https://handbook.gitlab.com/handbook/product/ux/ux-scorecards/). We use this label to help us easily find current work and track efforts over time.
    
- 
    
    [**UX scorecard-rec** label](https://gitlab.com/groups/gitlab-org/-/issues?scope=all&utf8=%E2%9C%93&state=opened&label_name[]=UX%20scorecard-rec): Indicates this issue is a recommendation that was a result of a UX scorecard review. It’s OK if the issue was created prior to the scorecard being done; it can still be pulled into the set of recommendations.
    
- 
    
    [**CM scorecard** label](https://gitlab.com/groups/gitlab-org/-/issues?sort=created_date&state=opened&label_name[]=CM+scorecard): Indicates the primary issue or epic for the [CM Scorecard](https://handbook.gitlab.com/handbook/product/ux/category-maturity/category-maturity-scorecards/). It is used to easily find current work and track efforts.
    
- 
    
    [**cm-scorecard-rec** label](https://gitlab.com/groups/gitlab-org/-/issues?sort=created_date&state=opened&label_name[]=cm-scorecard-rec): Indicates this issue is a recommendation that was a result of a CM Scorecard.
    
- 
    
    [Actionable Insights](https://handbook.gitlab.com/handbook/engineering/ux/ux-research/research-insights/#how-to-document-actionable-insights) document learnings from research that need to be acted on.
    
    - [Actionable Insight::Exploration needed](https://gitlab.com/groups/gitlab-org/-/issues/?sort=updated_desc&state=opened&label_name%5B%5D=Actionable%20Insight%3A%3AExploration%20needed): A research insight derived from a UX research study that requires further exploration.
    - [Actionable Insight::Product change](https://gitlab.com/groups/gitlab-org/-/issues/?sort=updated_desc&state=opened&label_name%5B%5D=Actionable%20Insight%3A%3AProduct%20change): A research insight derived from a UX research study and requires a change to the product experience.
- 
    
    [Type labels](https://handbook.gitlab.com/handbook/product/groups/product-analysis/engineering/metrics/#work-type-classification): Used to track feature, maintenance, and bug issues and MRs. UX Leadership are active participants in influencing the prioritization of all three work types. See also who are the [DRIs for prioritization](https://handbook.gitlab.com/handbook/product/product-processes/cross-functional-prioritization/#prioritization-for-feature-maintenance-and-bugs).
    
- 
    
    **Theme labels** can be created to group issues that solve a similar user experience problem but don’t have a category. This can be especially useful for a user experience that spans the product. These issues still require a UX label.
    
- 
    
    [**UX: Feature Discovery Improvement**](https://gitlab.com/groups/gitlab-org/-/issues?label_name%5B%5D=UX%3A++Feature+Discoverability+Improvement): Indicates issue may improve feature discoverability.
    
- 
    
    [**UX: Onboarding Improvement**](https://gitlab.com/groups/gitlab-org/-/issues/?label_name%5B%5D=UX%3A%20Onboarding%20Improvement): Indicates issue is a potential onboarding improvement.
    

## UX Calendar

The [UX Calendar](https://calendar.google.com/calendar/embed?src=gitlab.com_9psh26fha3e4mvhlrefusb619k%40group.calendar.google.com) (*internal only*) is the SSOT for our team meetings. You can find the details for UX calls, UX Forum, and other team meetings here. These meetings are open to everyone in GitLab. Anyone in the UX department can add events to the Google Calendar. Managers and above can make changes and manage sharing, while ICs can make changes to events. Please reach out in the `#ux_leadership` Slack channel with any questions or requests.

### UX All Hands

The UX All Hands meeting takes place every six weeks, with two sessions to accommodate both EMEA/AMER and APAC/AMER-friendly time zones.

The purpose is to share company updates, stay connected, and receive feedback.

The entire UX department is invited, though anyone at GitLab is welcome to attend and contribute to the [All Hands agenda](https://docs.google.com/document/d/1G52AWUbhrzPqihifeUpp0Q7vb_OChSC-iOKphUMsndI/edit?tab=t.0) (internal). As with all general meetings at GitLab, attendance is optional though encouraged, and will be recorded.

### Retrospectives

After each release, we have a company retrospective call in which we discuss what went well, what went wrong, and what we can improve for the next release.

To understand the specific challenges faced by the UX Department, we hold an async UX retrospective after every milestone. This retro is carried out through a new Issue created for the recent release in the [ux-retrospectives](https://gitlab.com/gl-retrospectives/ux-retrospectives/issues) project. The goal is to evaluate what went well, what didn’t go well, and how we can improve.

### UX Forum

The [UX Forum](https://handbook.gitlab.com/handbook/product/ux/ux-forum/) is a recurring meeting for UX team members to share and discuss their work. This includes past, current, or future work, and covers Product Design, UX Research, and Technical Writing. All meetings are recorded and made available on [Unfiltered](https://www.youtube.com/playlist?list=PL05JrBw4t0Kq89nFXtkVviaIfYQPptwJz) for Product, UX, Engineering, and Leadership to watch at their convenience.

## UX Week in Review

The [UX Week in Review](https://docs.google.com/document/d/1YCpTr_jXxIe8O8ULBDAJRC3kWD5SzVDdAHptiOYkQEM/edit?tab=t.0#heading=h.9qwiojcv4wzk) is an asynchronous document that includes important updates for everyone in the UX department. This doc is editable by anyone at GitLab and everyone can contribute.

Reminders are sent out weekly in the [#ux](https://gitlab.enterprise.slack.com/archives/C03MSG8B7) Slack channel to add and read updates. UX Managers will receive a monthly reminder in the [#ux_leadership](https://gitlab.enterprise.slack.com/archives/CPQT50BFG) Slack channel to add project updates from across their team.

## UX Talent Assessment

In UX, we utilize [performance factor worksheets](https://drive.google.com/drive/folders/1KgmIt7Umm0XH2-74jMBpOl67Yko1t2uK) (**🔒 internal only**) as a way to facilitate talent assessment and growth conversations between manager and their direct reports. These worksheets are available in Google Sheets format and the spreadsheets include tabs for a mid-year and year-end review, as well as a tab to list Achievement, Strengths, and Opportunities throughout the year.

It is strongly encouraged for each team member to have their own worksheet created at the start of the fiscal year so that it can be used as a tool throughout the entire year.

Performance factor worksheets can be utilized to help efficiently complete the year-end company [talent assessment program within Workday](https://handbook.gitlab.com/handbook/people-group/talent-assessment/).

## Meet some of our team members

- [Valerie Karnes](https://gitlab.com/vkarnes/readme) - Director of Product Design
- [Jacki Bauer](https://gitlab.com/jackib) - Product Design Manager
- [Justin Mandell](https://gitlab.com/jmandell/readme) - Product Design Manager
- [Taurie Davis](https://gitlab.com/tauriedavis/readme/blob/master/README.md) - Senior Product Design Manager
- [Rayana Verissimo](https://gitlab.com/rayana/readme) - Product Design Manager
- [Jeremy Elder](https://gitlab.com/jeldergl/view/blob/master/README.md) - Staff Product Designer, Foundations
- [Austin Regnery](https://gitlab.com/aregnery/dear-journal/-/blob/master/README.md) - Senior Product Designer
- [Anne Lasch](https://gitlab.com/alasch/about-anne/-/blob/master/README.md) - Senior UX Researcher
- [Emily Bauman](https://gitlab.com/emilybauman/about-me/-/blob/master/README.md) - Senior Product Designer
- [Will Leidheiser](https://gitlab.com/wleidheiser/about-will/-/blob/main/README.md) - Staff UX Researcher

### [Assessing Category Maturity](https://handbook.gitlab.com/handbook/product/ux/category-maturity/)

We assess the maturity of our product categories based on market evaluations and user testing

### [Competitor Evaluations](https://handbook.gitlab.com/handbook/product/ux/competitor-evaluations/)

Competitor evaluations help us understand how a competing product addresses the Jobs-To-Be-Done that our product also tries to address.

### [Design collaborator's playbook](https://handbook.gitlab.com/handbook/product/ux/collaborators-playbook/)

This page acts as a quick reference of mental models for sync and async collaboration.

### [Documenting research insights in Dovetail](https://handbook.gitlab.com/handbook/product/ux/dovetail/)

The GitLab UX Research team's guide to documenting insights in Dovetail

### [GitLab Navigation](https://handbook.gitlab.com/handbook/product/ux/navigation/)

The group::personal productivity team owns the navigation structures of the GitLab product. Please review this information if you plan to propose changes to GitLab navigation.

### [How to create a user persona](https://handbook.gitlab.com/handbook/product/ux/persona-creation/)

This page goes into detail around the steps needed to create a user persona with a high degree of confidence.

### [How we work](https://handbook.gitlab.com/handbook/product/ux/how-we-work/)

Guidance on how the UX Department at GitLab works.

### [Jobs to be Done at GitLab](https://handbook.gitlab.com/handbook/product/ux/jobs-to-be-done/)

Jobs to be Done (JTBD) is a framework for viewing products and solutions from the user's perspective, focusing on the problems they want to solve rather than specific solutions. It helps GitLab team members uncover user needs, identify strategic opportunities, validate plans, and drive innovation.

### [Pajamas Design System](https://handbook.gitlab.com/handbook/product/ux/pajamas-design-system/)

The goal of Pajamas is to be the single source of truth for the robust library of UI components that we use to build the GitLab product

### [Product Design](https://handbook.gitlab.com/handbook/product/ux/product-design/)

At GitLab, our Product Design team drives the business forward by becoming experts in their specific stage groups staying informed about the entire product, and aligning with user and business goals. We partner closely with our stable counterparts in Product Management and Development to deliver exceptional user experiences.

### [Product Designer Workflow](https://handbook.gitlab.com/handbook/product/ux/product-designer/)

Here are some guidelines to help Product Designers manage their work at GitLab

### [Remote Design Sprint](https://handbook.gitlab.com/handbook/product/ux/design-sprint/)

The purpose of a Remote Design Sprint is to create a shared understanding and a solution to a problem following a specific process over a set timeframe. Remote Design Sprint process is based on [Google's Design Sprint methodology](https://designsprintkit.withgoogle.com/methodology/overview), and adjusted using [AJ&Smart's Remote Design Sprint 2.0](https://drive.google.com/file/d/16bwrAqHVf8qxovd87Q7LdzqwAgy7a6Rx/view).

### [Technical Writing](https://handbook.gitlab.com/handbook/product/ux/technical-writing/)

The GitLab Technical Writing team collaborates with developers, product managers, and the community to develop product documentation.

Good documentation meets the evolving needs of GitLab customers, users, and administrators. It educates readers about features and best practices. It enables people to efficiently configure, use, and troubleshoot GitLab. The Technical Writing team manages the [docs.gitlab.com](https://docs.gitlab.com/) site and its content, processes, and tooling.

The [documentation roadmap](https://gitlab.com/groups/gitlab-org/-/epics/4602) drives our efforts to improve both the content and [documentation website](https://docs.gitlab.com/). For example, we know that people have trouble finding information on docs.gitlab.com. We have roadmap items and OKRs to replatform the docs site, provide better task-based information, and make content easier to find. These larger projects, completed in addition to feature documentation, provide continual, iterative improvement to the user experience of our documentation.

### [Think Big & Think Small Meetings](https://handbook.gitlab.com/handbook/product/ux/thinkbig/)

The purpose of think big & think small meetings is to develop a shared understanding of goals by discussing vision, roadmap, research, design, and delivery of upcoming features.

### [UX Department Learning and Development](https://handbook.gitlab.com/handbook/product/ux/learning-and-development/)

This page contains links to internal and external resources that members of the UX Department at GitLab can use to build their skills.

### [UX Department Performance Indicators](https://handbook.gitlab.com/handbook/product/ux/performance-indicators/)

Performance indicators for the UX department at GitLab

### [UX Forum](https://handbook.gitlab.com/handbook/product/ux/ux-forum/)

The UX Forum is a recurring meeting for UX team members to share and discuss their work.

### [UX Heuristics](https://handbook.gitlab.com/handbook/product/ux/heuristics/)

Heuristics used by the UX team to evaluate our product.

### [UX Research at GitLab](https://handbook.gitlab.com/handbook/product/ux/ux-research/)

The UX Research team delivers key and timely insights to drive user-centric innovation, support and influence decisions from design tactics to product strategy.

### [UX Research Operations (ReOps) at GitLab](https://handbook.gitlab.com/handbook/product/ux/ux-research-coordination/)

We empower UX Research DRIs with the resources needed for efficient and high-quality research, enabling team members to focus on generating insights that drive exceptional user experiences and product innovation.

### [UX Resources](https://handbook.gitlab.com/handbook/product/ux/ux-resources/)

This page includes information about UX Resources to help you do your job as a product desginer at GitLab.

### [UX Scorecards](https://handbook.gitlab.com/handbook/product/ux/ux-scorecards/)

The UX Scorecard is a process similar to a heuristic evaluation that helps identify usability issues and score a given experience.