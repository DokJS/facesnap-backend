
# Facesnap API

This repository contains a minimal api developed using express JS. To properly run this backend you have to run commands below:

1 - npm install
2 - npm run start


This backend will run at your 3000 port, so the base url is : http://localhost:3000/



API Documentation : 

    GET /facesnaps will returns a list of faceSnap
    GET /facesnaps/${id} will returns a specific faceSnap
    POST /facesnaps, used to create a faceSnap will returns the faceSnap created



Models :


FaceSnap : {
  id: number;
  title: string;
  description: string;
  createdDate: Date;
  snaps: number;
  imageUrl: string;
  location?: string;
  snapped?: boolean;
}


FormData : {
  title: string;
  description: string;
  imageUrl: string;
  location?: string;
}
