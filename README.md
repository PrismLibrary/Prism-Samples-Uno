# Prism Samples for Uno Platform

The samples in this repo demonstrate how to use various Prism features with Uno Platform and WinUI 3. If you are just getting started with Prism, it is recommended that you start from the first sample, and work your way down the list sequentially (in order). Each sample builds on the previous sample's concept.

| Topic | Description |
-----------|-------------|
| [PrismApplication and the Shell][PrismApplicationShell] | Create a basic PrismApplication and Shell |
| [Regions][Regions] | Create a region |
| [Custom Region Adapter][CustomRegionAdapter] | Create a custom region adapter for the StackPanel |
| [View Discovery][ViewDiscovery] | Automatically inject views with View Discovery |
| [View Injection][ViewInjection] | Manually add and remove views using View Injection |
| [View Activation/Deactivation][ViewActivationDeactivation] | Manually activate and deactivate views |
| [Modules with Code][ModulesCode] | Load modules using code |
| [Modules loaded manually][ModulesManuallyLoaded] | Load modules manually using the IModuleManager |
| [ViewModelLocator][ViewModelLocator] | using the ViewModelLocator |
| [ViewModelLocator - Change Convention][ViewModelLocatorCustomConvention] | Change the ViewModelLocator naming conventions |
| [ViewModelLocator - Custom Registrations][ViewModelLocatorRegistrations] | Manually register ViewModels for specific views |
| [DelegateCommand][DelegateCommand] | Use DelegateCommand and `DelegateCommand<T>` |
| [CompositeCommands][CompositeCommands] | Learn how to use CompositeCommands to invoke multiple commands as a single command |
| [IActiveAware Commands][ActiveAware] | Make your commands IActiveAware to invoke only the active command |
| [Event Aggregator][EventAggregator] | Using the IEventAggregator |
| [Event Aggregator - Filter Events][EventAggregatorFilterEvents] | Filtering events when subscribing to events |
| [RegionContext][RegionContext] | Pass data to nested regions using the RegionContext |
| [Region Navigation][RegionNavigation] | See how to implement basic region navigation |
| [Navigation Callback][NavigationCallback] | Get notifications when navigation has completed |
| [Navigation Participation][NavigationParticipation] | Learn about View and ViewModel navigation participation with INavigationAware |
| [Navigate to existing Views][NavigateExistingViews] | Control view instances during navigation |
| [Passing Parameters][PassingParameters] | Pass parameters from View/ViewModel to another View/ViewModel |
| [Confirm/cancel Navigation][CancelConfirmNavigation] | Use the IConfirmNavigationRequest interface to confirm or cancel navigation |
| [Controlling View lifetime][ControllingViewLifetime] | Automatically remove views from memory with IRegionMemberLifetime |
| [Navigation Journal][NavigationJournal] | Learn how to use the Navigation Journal |
<!-- | [Interactivity - NotificationRequest][28] | Learn how to show popups using an InteractionRequest |
| [Interactivity - ConfirmationRequest][29] | Learn how to prompt a confirmation dialog using a ConfirmationRequest |
| [Interactivity - Custom Content][30] | Learn how to use your own content for a dialog shown with InteractionRequest |
| [Interactivity - Custom Request][31] | Create your own custom request to use with an InteractionRequest |
| [Interactivity - InvokeCommandAction][32] | Invoke commands in response to any event | -->


[PrismApplicationShell]: 01-PrismApplicationShell/
[Regions]: 02-Regions/
[CustomRegionAdapter]: 03-CustomRegions/
[ViewDiscovery]: 04-ViewDiscovery/
[ViewInjection]: 05-ViewInjection/
[ViewActivationDeactivation]: 06-ViewActivationDeactivation/
[ModulesCode]: 07-Modules%20-%20Code/
[ModulesManuallyLoaded]: 07-Modules%20-%20LoadManual/
[ViewModelLocator]: 08-ViewModelLocator/
[ViewModelLocatorCustomConvention]: 09-ChangeConvention/
[ViewModelLocatorRegistrations]: 10-CustomRegistrations/
[DelegateCommand]: 11-UsingDelegateCommands/
[CompositeCommands]: 12-UsingCompositeCommands/
[ActiveAware]: 13-IActiveAwareCommands/
[EventAggregator]: 14-UsingEventAggregator/
[EventAggregatorFilterEvents]: 15-FilteringEvents/
[RegionContext]: 16-RegionContext/
[RegionNavigation]: 17-BasicRegionNavigation/
[NavigationCallback]: 18-NavigationCallback/
[NavigationParticipation]: 19-NavigationParticipation/
[NavigateExistingViews]: 20-NavigateToExistingViews/
[PassingParameters]: 21-PassingParameters/
[CancelConfirmNavigation]: 22-ConfirmCancelNavigation/
[ControllingViewLifetime]: 23-RegionMemberLifetime/
[NavigationJournal]: 24-NavigationJournal/
<!-- [28]: 25-NotificationRequest/
[29]: 26-ConfirmationRequest/
[30]: 27-CustomContent/
[31]: 28-CustomRequest/
[32]: 29-InvokeCommandAction/ -->

