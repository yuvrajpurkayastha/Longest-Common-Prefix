# Longest-Common-Prefix

IF string x is smaller than y
	    //check for common prefix part on basis of x
		    FOR( i=0;i<length of string x; i++)
		    IF(x[i]==y[i])
		    result+=x[i]; //append the common character
			    ELSE//no common character at this point
			    Returnresult
		    END FOR
	
	    ELSE//if string y is smaller than x
	    //check for common prefix part on basis of y		
		    FOR (i=0;i<length of y; i++)
		    IF(y[i]==x[i])
		    result+=y[i];//append the common character
		    ELSE//no common character at this point
		     return result;
		    END FOR
	    END IF-ELSE
