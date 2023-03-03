# Theme 1: Provide Technology Educators Information and Links to Resources to Improve their Courses and Teaching. 
## Overview
This theme covers breakdown of actual development tasks necessary to deliver a minimally viable product.
## Initiative(s)
* [Develop a web-based application that provides curated content for technology education](initiatives/initiative_develop_web_based_app_for_educators.md)
  ### Epic(s)
   * [Project Infra and Initial Setup](initiatives/epics/epic_project_infra_and_initial_setup.md)
     #### Stories
      * [Modern and Scalable](initiatives/epics/stories/story_modern_and_scalable.md)
        #### Tasks
        * [Research Cloud Environments](initiatives/epics/stories/tasks/task_research_cloud_environments.md)
        * [Implement Docker for Automating Deployment](initiatives/epics/stories/tasks/task_implement_docker_deployment_automation.md)
      * [Node and NPM](initiatives/epics/stories/story_node_npm_standard.md)
        #### Tasks
        * [Setup and Validate Node with NPM](initiatives/epics/stories/tasks/task_setup_validate_node_npm.md)  
      * [Linting and Formatting Standards](initiatives/epics/stories/story_linting_standard.md)
        #### Tasks
         * [Setup Linting and Formatting Standards](initiatives/epics/stories/tasks/task_setup_linting_prettier_standard.md)
      * [Webpack Config](initiatives/epics/stories/story_webpack_setup_config.md)
        #### Tasks
         * [Webpack Setup Config](initiatives/epics/stories/tasks/task_webpack_setup_configure.md) 
      * [Bootstrap Config](initiatives/epics/stories/story_ux_bootstrap.md)
        #### Tasks
         * [Bootstrap Setup and Config](initiatives/epics/stories/tasks/task_bootstrap_setup_config.md) 
      * [Testing](initiatives/epics/stories/story_testing_frameworks.md)
        #### Tasks
         * [Testing Library Setup](initiatives/epics/stories/tasks/task_testing_library_setup.md) 
     
  * [MyWebClass Base Site Creation](initiatives/epics/epic_mywebclass_site_creation.md)
    #### Stories
     * [Compile Links and Resources](initiatives/epics/stories/story_links_information_courses.md)
       #### Tasks
        *  [Compile List of Links and Resources](initiatives/epics/stories/tasks/task_compile_list_links_resources.md)
        * [Filter and Rank List](initiatives/epics/stories/tasks/task_filter_rank_curated_list.md)
        * [Display Curated List](initiatives/epics/stories/tasks/task_display_curated_list.md)
     * [Intuitive Navigation](initiatives/epics/stories/story_user_navigation.md)
       #### Tasks
        * [Navigation Setup](initiatives/epics/stories/tasks/task_navigation_setup.md)
     * [Site Breadcrumbs](initiatives/epics/stories/story_breadcrumbs.md)
       #### Tasks
        * [Add Breadcrumbs](initiatives/epics/stories/tasks/task_breadcrumbs_addition.md) 
     * [Enhanced Landing](initiatives/epics/stories/story_enhanced_landing_page.md)
       #### Tasks
        * [Create and Enhance Landing Page](initiatives/epics/stories/tasks/task_enhance_landing_page.md) 
     * [Rich Media Content](initiatives/epics/stories/story_rich_content.md)
       #### Tasks
        * [Video or Rich Media](initiatives/epics/stories/tasks/task_video_or_rich_media_add.md)
  * [MyWebClass SEO and Analytics](initiatives/epics/epic_mywebclass_seo_analytics.md)
    #### Stories
     * [Search Engine Optimization](initiatives/epics/stories/story_search_engine_optimization.md)
     * [Site Analytics](initiatives/epics/stories/story_site_analytics.md)
  * [Legal Compliance and Validation](initiatives/epics/epic_legal_compliance.md)
    #### Stories
     * [User Information Handling](initiatives/epics/stories/story_user_information_handling.md)
     * [Legal Compliance Validation](initiatives/epics/stories/story_legal_compliance_validation.md)
  * [Automatic Deployment and Testing](initiatives/epics/epic_automatic_deployment_and_testing.md)
    #### Stories
     * [CI/CD Pipelines](initiatives/epics/stories/story_ci_cd_pipelines.md)
     * [Code Standard Validation](initiatives/epics/stories/story_code_standard_validation.md)

## Test plan
Site will be tested iteratively and automatically before each release for Code Review, and before Prod deployment. 
Will make use of libraries such as Jest and Playwright to facilitate this.