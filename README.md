You should copy this code to your ide 


   import com.google.appinventor.components.annotations.DesignerComponent;
import com.google.appinventor.components.annotations.SimpleObject;
import com.google.appinventor.components.annotations.SimpleFunction;
import com.google.appinventor.components.annotations.SimpleEvent;
import com.google.appinventor.components.annotations.SimpleProperty;
import com.google.appinventor.components.common.ComponentCategory;
import com.google.appinventor.components.runtime.AndroidNonvisibleComponent;
import com.google.appinventor.components.runtime.AndroidViewComponent;
import com.google.appinventor.components.runtime.ComponentContainer;
import com.google.appinventor.components.runtime.EventDispatcher;

@DesignerComponent(version = 1,
                    category = ComponentCategory.EXTENSION,
                    description = "",
                    nonVisible = true,
                    iconName = "")

@SimpleObject(external = true)

public class Gradient extends AndroidNonvisibleComponent {
    
    public Gradient(ComponentContainer container) {
        super(container.$form());
    }
    
    // Write your code here.
}
