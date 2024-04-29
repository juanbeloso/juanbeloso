import SoftwareDeveloper from 'juanBeloso';

class Bio extends SoftwareDeveloper {
  name = 'Juan Beloso';
  pronouns: "he" | "him":
  passions: 'Quality Assurance','performance web', 'web development';
  title    = 'QA tester';
  company  = 'HeyWeb | Remote';
  location = 'Spain';
}

class Skills extends SoftwareDeveloper {
  languages  = [Javascript, Typescript, HTML, CSS, Java];
  databases  = ['MySQL', 'MongoDB', 'PostgreSQL', 'SQLServer'];
  frameworks = ['Laravel', 'Filament'];
}
