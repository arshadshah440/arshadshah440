Hi there 👋

Who is this?
$me = Human::create(
    first_name: 'Arshad',
    last_name: 'shah',
    linkedin: 'https://www.linkedin.com/in/dev-arshad-shah/',
);

$me->educations()->saveMany(
    new Education(
        institution: 'University of Sargodha',
        degree: 'Bachelor of computer Science',
        subject: 'Computer Science',
        graduated: 2022
    )
);
What are you my skills?
{
    "name": "bilfeldt/skills",
    "type": "Skills",
    "description": "My Skills",
    "keywords": [
        "php",
        "javascript",
        "JQuery",
        "AJAX",
        "React.js"
    ],
}
