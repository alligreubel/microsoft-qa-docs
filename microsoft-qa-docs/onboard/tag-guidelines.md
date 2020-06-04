# Tag creation guidelines to onboard your service to Microsoft Q&A

Microsoft Q&A is based on tags and part of the docs.microsoft.com (Docs) ecosystem. Therefore, we are aligning our tag taxonomy to Docs, so we can do integration such as recommendations from other Docs offerings such as documentation and Learn and also pe.

Therefore, partners provide tag candidates for their services on Q&A, which get reviewed and updated by the Dev Relations Information Architect for consistency in our Docs ecosystem. 

Moreover, to ensure consistency, all the tags will be created and maintain by the Dev Relations team.

> [!IMPORTANT]
> These are general guidelines that attempt to cover a range of cases. We will work with you to ensure the tags make the most sense for your audience while align with your service offerings and Docs structure.

## Microsoft Q&A tag elements

Microsoft Q&A tags have the following elements:

1. [Tag status](#tag-status)
1. [Tag level or hierarchy](#tag-level-or-hierarchy)
1. [Tag name](#tag-name)
1. [Tag description](#tag-description)
1. [Tag icon](#tag-icon)

### Tag status

*This is an optional field.*

Tag status is indicates whether the tag will be visible for the users or just used for reporting.

Possible statuses are:

- Visible. Users can see and use the tag for their posts.
- Invisible. The users cannot use this tag for any post. It is only used for hierarchy and reporting purposes.

### Tag level or hierarchy

*This is a mandatory field.*

In Microsoft Q&A, tags can have a hierarchy (i.e. a parent-child relationship):

- Level 1 (L1). Tag at this level is usually the brand the product/service belongs to. For example, "azure", "windows". As this tag is very general, it might not be used for tagging, and it should be *Invisible* to users.
- Level 2 (L2). Depending on your brand offering, you might use this level for a category or offering (for example, *Azure Compute*), or for an actual service name (for example, *Dynamics Commerce*). If the tag represents a category or an offering, then this tags is marked as invisible; otherwise, it is visible.
- Level 3 (L3). This level is necessary if your L2 tag is not a category. This tag should denote your service name

We believe that we should stay as high-levels with tags as possible to make them easily identified by users. However, if you need Level 4 (L4) tags, provide the following information:

- A customer-facing citation for these values (somewhere they’re used where they’ve been vetted by branding/CELA/etc. so we can make sure they’re valid and not opening us up to legal trouble.)
- A business justification of why these tags are needed and how they will be used.

### Tag name

*This is a mandatory field.*

- Please review the [Docs taxonomy](https://review.docs.microsoft.com/en-us/new-hope/information-architecture/metadata/taxonomies?branch=master) page and use tags already used in Docs.
- Tag names are only for official brands/products/services, or groupings/categories used in Docs, ACOM, or any other major site to match the offering users.
- Tags are in lowercase even if they refer to a proper noun. Example: *azure*.
- Tags do not contain spaces and follow kebab casing by combining words and replacing each space with a hyphen (-). Example: *azure-active-directory*.
- Except for hyphens, tags do not have any other special characters.
- Tag names are as compact as possible, yet the user understands them. Example: instead of using  *common-data-service-for-apps* use *common-data-service*.
- Tag names do not contain "microsoft" , unless it is needed as a dissambiguator. Example: *ms-graph*.
- Tags do not contain product versions in the tags, unless there really needs to be an exception.
- To ensure customers can correctly associate the tags to the right service, Level 2 tag names start with the L1 tag name. Example:
    - L1 tag: *azure*
    - L2 tag: *azure-compute*
- Level 3 tags have the L1 tag name, but they don't have the L2 tag name, unless it is necessary.
    - L1 tag: *azure*
    - L2 tag *azure-compute*
    - L3 tag: *azure-active-directory*

### Tag description

*This is a mandatory field for any visible tag. For invisible tags, Dev Relations will provide a canned description applicable to all the invisible tags: "This tag is not available to the users to tag content. It is only used for reporting and hierarchy purposes.".*

Tag descriptions help customers to better understand which service the tag represents.

- All tag descriptions start with "Questions about..."
- All tag descriptions should be short and to the point. Try to keep them under 255 characters if possible.

### Tag icon

*This is an optional field.*

- Tag icons are included in a zip folder or direct links if they are in a web site.
- Icons can be in SVG, PNG, JPG, or GIF format.
- Icons are not animated.

## Template

Provide the tag information following this [Q&A tags template](https://microsoft.sharepoint.com/:x:/t/CE_APEX/ET0zpsPxys9OjwHM55mftCgBHeKGIfX1NywjKX6USs6_-Q?e=fXOEMs) spreadsheet.

Send the spreadsheet to [Sandra Aldana](mailto:saldana)

## Resources

- [Docs taxonomy](https://review.docs.microsoft.com/en-us/new-hope/information-architecture/metadata/taxonomies?branch=master)
