import { SoftwareDeveloper } from '@riqueef';

class Bio extends SoftwareDeveloper {
  name     = 'Henrique Castro';
  title    = 'Full-stack developer';
  location = 'São Paulo, SP';
  website  = 'https://henriquefelix.tech';
}

class Skills extends SoftwareDeveloper {
  languages  = ['JavaScript', 'Python' ];
  databases  = ['MySQL', 'MongoDB', 'PostgreSQL'];
  frameworks = ['React', 'Angular', 'Nextjs', 'Nodejs', 'Django'];
}
