# wp-Family-Enroll Plugin

A custom registration system for the ListingHive WordPress theme where users can register family members and enroll them in programs based on eligibility criteria.

## Features

- Allows users to register multiple family members.
- Stores and manages family member profiles.
- Provides eligibility criteria for listings (age, gender).
- Validates family member details against listing requirements before registration.

## Installation

### Prerequisites

- WordPress installation.
- ListingHive theme installed and activated.
- Advanced Custom Fields (ACF) plugin installed and activated or use custom metaboxes.

### Steps

1. **Download the Plugin:**

   Download the plugin from the [GitHub repository](https://github.com/yourusername/wp-Family-enroll).

2. **Upload the Plugin:**

   Upload the plugin folder to your WordPress installation. You can do this via FTP or through the WordPress admin dashboard:

   - Via FTP:
     - Extract the downloaded plugin folder.
     - Upload the extracted folder to the `/wp-content/plugins/` directory on your server.

   - Via WordPress Admin Dashboard:
     - Go to `Plugins > Add New`.
     - Click `Upload Plugin`.
     - Choose the downloaded zip file and click `Install Now`.
     - Activate the plugin.

3. **Activate the Plugin:**

   Go to `Plugins > Installed Plugins` and activate the `wp-Family-Enroll` plugin.

4. **Configure Custom Fields (If using ACF):**

   - Go to `Custom Fields > Add New`.
   - Create a new field group named "Listing Eligibility Criteria".
   - Add the following fields:
     - Minimum Age: Field Name `min_age`, Field Type `Number`.
     - Maximum Age: Field Name `max_age`, Field Type `Number`.
     - Gender: Field Name `gender`, Field Type `Select`, Choices `Male` and `Female`.
   - Set the location rule to display these fields for the listing post type.

## Usage

1. **Add Family Members:**

   - Go to your user profile page.
   - Fill in the family member registration form (name, age, gender) and submit.

2. **View and Manage Family Members:**

   - View the list of registered family members on your user profile page.
   - Delete family members if needed.

3. **Register for Listings:**

   - View available listings.
   - Select a listing and register a family member based on the eligibility criteria.
   - The system will validate the family member's details against the listing requirements before allowing registration.


