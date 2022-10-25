public class Job implements Runnable {
	private int jobNumber;

 	Job (int jobNumber) {
 		this.jobNumber = jobNumber;
 	}

 	public void run () {
 	// Undertake required work, here we will emulate it by sleeping for a period
	 System.out.println ("Job: " + jobNumber + " is being processed by thread : "
 		+ Thread.currentThread ().getName());
 	try {
 		Thread.sleep((int)(1000));
 	} catch (InterruptedException e) {
 		// no catching as example should not experience interruptions
 	}
 	System.out.println("Job: " + jobNumber + " is ending in thread : "
 		+ Thread.currentThread().getName());
   }

}
